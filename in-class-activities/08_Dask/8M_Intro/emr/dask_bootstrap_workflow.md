# Launching a Dask Cluster with AWS EMR

To launch a Dask-compatible EMR cluster, you should first upload the bootstrap-dask script provided in this directory to an S3 bucket that you have access to (I uploaded mine to the aws-emr-resources bucket that AWS automatically created for storing EMR notebooks that we launched last week). This bootstrap script installs Miniconda, Dask, and some other Python packages to your EMR cluster (you can add additional packages via the --bootstrap-actions "Args", as in the example below). It also launches a Jupyter Server on the cluster for you, so that you can use Dask in a Jupyter notebook environment.

Run the following on your local terminal (wherever you installed AWS CLI) or on the AWS Academy Lab terminal to launch your cluster. Note that you should provide the S3 location that you uploaded your bootstrap script (or just use mine -- it's publicly accessible for the duration of this class). You should also provide the name of your PEM file in the --ec2-attributes "KeyName" field (we're using the default AWS Academy "vockey" here). Note as well that you can launch whatever types of instances and counts that you wish. Here, we launch 3 m5.xlarge instances in our cluster: 1 instance for the EMR resource manager and 2 worker instances.

```
aws emr create-cluster --name "Dask-Cluster" \
    --release-label emr-6.3.0 \
    --applications Name=Hadoop \
    --instance-type m5.xlarge \
    --instance-count 3 \
    --bootstrap-actions Path=s3://aws-emr-resources-459674479721-us-east-1/bootstrap-dask,Args="[--conda-packages,fastparquet,python-snappy,snappy,matplotlib]" \
    --use-default-roles \
    --region us-east-1 \
    --ec2-attributes '{"KeyName":"vockey"}'
```

It can take ten to twenty minutes for your cluster to launch. While the cluster is launching, you'll want to adjust the permissions of the Security Group associated with your "Master" EC2 instance in the cluster so that it will allow you to ssh into it. To do so, you'll need to access the Summary tab of your EMR cluster in the AWS Console and scroll down to the "Security and access" header. Click the security group ID number that is beside the "Security groups for Master" description. On the next screen, click this same security group ID again (corresponding to the name "ElasticMapReduce-master"). Now click the "Edit inbound rules" button and add an inbound rule of type "SSH" and Source type "Anywhere" (you can also limit ssh access to your IP if you'd like for this to be more secure) to your cluster. Finally, click "save rules" to save your new inbound rule.

Once your cluster has finished bootstrapping and is running, you can issue the following command on your local machine terminal (assuming a Unix-style terminal) to forward port 8888 from the Jupyter server running on the cluster to your local port 8888 (entering the path to your PEM file along with the correct address for your master node, which is available after the "Master public DNS" header in your cluster's summary tab in the AWS EMR console):

```
ssh -NL localhost:8888:localhost:8888 -i ~/.ssh/labsuser.pem hadoop@YOUR_ADDRESS_HERE
```

Be sure to keep this local terminal window open to maintain your connection to the cluster. Now, if you go to `localhost:8888` in the web browser on your local machine, you can log in to your Dask cluster! The default password for the Jupyter server is `dask-user`. To test to see if Dask is correctly configured, try running the short "Dask on an EMR Cluster" Jupyter notebook provided here in this directory (just upload it from within your Jupyter window and run it). The notebook demonstrates how you can launch your cluster and perform basic Dask array and DataFrame operations that scale up the capabilities of Python libraries like NumPy and Pandas.

When you're done, **remember to save your work and download anything you want to save back to your local machine** (you can do this by clicking File>Download as>.ipynb), or wherever you are saving your files. When you have everything saved, remember to terminate your EMR cluster (you can do this via the AWS CLI or the AWS Console). You will be charged for as long as your EC2 instances are running.
