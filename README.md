# Large-Scale Computing for the Social Sciences
### Spring 2022 - MACS 30123/MAPS 30123/PLSC 30123

| Instructor Information       | **TA Information**      | **TA Information**     | Course Information     |
| :-------------               | :-------------          | :-------------         | :------------          |
| Jon Clindaniel               | Jinfei Zhu              | MengChen Chung         | Location: 1155 E. 60th Street, Rm. 295   |
| 1155 E. 60th Street, Rm. 215 | Remote office hours only | In-person OH: 1155 E. 60th St., Rm 224 | Monday/Wednesday       |
| jclindaniel@uchicago.edu     | jinfei@uchicago.edu | mengchenc@uchicago.edu | 9:30-11:20 AM (CT) |
| **Office Hours:** [Schedule an Appointment](https://appoint.ly/s/jclindaniel/office-hours)\* <br/><br/> Drop-In (No appointment needed): Friday 9:00-11:00am | **Office Hours:** [Schedule an Appointment](https://appoint.ly/s/jinfei/office-hours)\* | **Office Hours:** [Schedule an Appointment](https://appoint.ly/s/mengchenc/LSC)\*| [Canvas Course Site](https://canvas.uchicago.edu/courses/41990) |

\* Scheduled Office Hours may be held via Zoom or in person if you prefer (just let us know which option you choose when you schedule your appointment via the Appoint.ly links above).

## Course Description
Computational social scientists increasingly need to grapple with data that is either too big for a local machine and/or code that is too resource intensive to process on a local machine. In this course, students will learn how to effectively scale their computational methods beyond their local machines. The focus of the course will be social scientific applications, ranging from training machine learning models on large economic time series to processing and analyzing social media data in real-time. Students will be introduced to several large-scale computing frameworks such as MPI, MapReduce, Spark, Dask, and OpenCL, with a special emphasis on employing these frameworks using cloud resources and the Python programming language.

*Prerequisites: MACS 30121 and MACS 30122, or equivalent (e.g. CAPP 30121 and CAPP 30122).*

## Course Structure
This course is structured into several modules, or overarching thematic learning units, focused on teaching students fundamental large-scale computing concepts, as well as giving them the opportunity to apply these concepts to Computational Social Science research problems. Students can access the readings, assignments, and resources for each of the class sessions within these modules on the [Canvas course site](https://canvas.uchicago.edu/courses/41990). If students have any questions about the course content, they should post these questions in the Ed Discussion forum for the course, which they can access by clicking the "Ed Discussion" tab on the left side of the screen on the Canvas course site. To see an overall schedule and syllabus for the course, as well as access additional course-related files (which we will walk through in in-class activities), students should visit (and clone/fork) the GitHub Course Repository, available here.

During regular class hours (9:30-11:20 AM CT on Mondays and Wednesdays), we will meet in 1155 E. 60th Street, Room 295 for a mixture of lecture, group activities, and in-class coding exercises related to the topic for the day. Attendance to the class sessions is mandatory and is an important component of the final course grade. Students should prepare for these classes by reading the assigned readings ahead of every session. All readings are available online and are linked in the course schedule below (and in the corresponding module on Canvas).

In order to practice large-scale computing skills and complete the course assignments, students will be given free access to UChicago's [Midway Cluster](https://rcc.uchicago.edu/docs/), [Amazon Web Services (AWS)](https://aws.amazon.com/) cloud computing resources, and [DataCamp](https://www.datacamp.com/). More information about accessing these resources will be provided to registered students in the first several weeks of the quarter.

## Grading
There will be an assignment due at the end of each unit (3 in total). Each assignment is worth 20% of the overall grade, with all assignments together worth a total of 60%. Additionally, attendance and participation will be worth 10% of the overall grade. Finally, students will complete a final project that is worth 30% of the overall grade (25% for the project itself, and 5% for an end-of-quarter video presentation).

| Course Component         | Grade Percentage  |
| :-------------           | :-------------    |
| Assignments (Total: 3)   | 60%               |
| Attendance/Participation | 10%               |
| Final Project            | 5% (Presentation) |
|                          | 25% (Project)     |

Grades are not curved in this class or, at least, not in the traditional sense. We use a standard set of grade boundaries:
* 95-100: A
* 90-95: A-
* 85-90: B+
* 80-85: B
* 75-80: B-
* 70-75: C+
* <70: Dealt on a case-by-case basis

We curve only to the extent we might lower the boundaries for one or more letter grades, depending on the distribution of the raw scores. We will not raise the boundaries in response to the distribution.

So, for example, if you have a total score of 82 in the course, you are guaranteed to get, at least, a B (but may potentially get a higher grade if the boundary for a B+ is lowered).

## Participation Expectations
We expect all students to participate in each class session in person (unless you have received authorization from the University to take the course remotely). Your participation grade (10% of your overall grade in the class) will be based on this in-class participation (70% of the participation grade) as well as your participation in answering peer questions on the Ed Discussion board (30% of the participation grade).

**If you are feeling sick (or have any possible COVID-19 symptoms), however, please stay home!** You can complete an alternative, [asynchronous option for meeting the participation requirement for that day](https://edstem.org/us/courses/21048/discussion/1326213). Note that remote course access for longer than two weeks will require approval from the Dean of Students office (contact Brett Baker at bbaker@uchicago.edu for more details). Finally, if you do have COVID-19 symptoms and/or test positive for COVID-19, be sure to follow the [University COVID-19 Protocol](https://goforward.uchicago.edu/health-requirements/) in addition to completing the above steps.

## Final Project
For their final project (due June 3rd, 2022), students will write large-scale computing code that solves a social science research problem of their choosing. For instance, students might perform a computationally intensive demographic simulation, or they may choose to collect, analyze, and visualize large social media data, or do something else that employs large-scale computing strategies. Students will additionally record a short video presentation about their project. Detailed descriptions and grading rubrics for the project and presentation are available [on the Canvas course site.](https://canvas.uchicago.edu/courses/41990)

## Late Assignments/Projects
Unexcused Late Assignment/Project Submissions will be penalized 10 percentage points for every hour they are late. For example, if an assignment is due on Wednesday at 2:00pm, the following percentage points will be deducted based on the time stamp of the last commit.

| Example last commit |	Percentage points deducted         |
| ----                | ----                               |
| 2:01pm to 3:00pm    |	-10 percentage points              |
| 3:01pm to 4:00pm    |-20 percentage points               |
| 4:01pm to 5:00pm    | -30 percentage points              |
| 5:01pm to 6:00pm    | -40 percentage points              |
| ...                 |	...                                |
| 11:01pm and beyond  |	-100 percentage points (no credit) |

If, for whatever reason, you need an extension on an assignment or project deadline, send a private message to the course staff **ahead of the assignment deadline** on the class Ed Discussion forum and we will evaluate these requests on a case-by-case basis.

## Plagiarism on Assignments/Projects
Academic honesty is an extremely important principle in academia and at the University of Chicago.
* Writing assignments must quote and cite any excerpts taken from another work.
* If the cited work is the particular paper referenced in the Assignment, no works cited or references are necessary at the end of the composition.
* If the cited work is not the particular paper referenced in the Assignment, you MUST include a works cited or references section at the end of the composition.
* Any copying of other students' work will result in a zero grade and potential further academic discipline.
If you have any questions about citations and references, consult with your instructor.

## Statement of Diversity and Inclusion
The University of Chicago is committed to diversity and rigorous inquiry from multiple perspectives. The MAPSS, CIR, and Computation programs share this commitment and seek to foster productive learning environments based upon inclusion, open communication, and mutual respect for a diverse range of identities, experiences, and positions.

Any suggestions for how we might further such objectives both in and outside the classroom are appreciated and will be given serious consideration. Please share your suggestions or concerns with your instructor, your preceptor, or your program’s Diversity and Inclusion representatives: Darcy Heuring (MAPSS), Matthias Staisch (CIR), and Chad Cyrenne (Computation). You are also welcome and encouraged to contact the Faculty Director of your program.

This course is open to all students who meet the academic requirements for participation. Any student who has a documented need for accommodation should contact Student Disability Services (773-702-6000 or disabilities@uchicago.edu) and the instructor as soon as possible.

## Course Schedule
| Unit   | Week | Day | Topic | Readings | Assignment |
| --- | --- | --- | --- | --- |  --- |
| Fundamentals of Large-Scale Computing | Week 1: Introduction to Large-Scale Computing for the Social Sciences | 3/28/2022 | Introduction to the Course | | |
|   |   | 3/30/2022 | General Considerations for Large-Scale Computing  | [Robey and Zamora 2021 (Chapter 1)](https://livebook.manning.com/book/parallel-and-high-performance-computing/chapter-1), [Faster code via static typing (Cython)](http://docs.cython.org/en/latest/src/quickstart/cythonize.html), [A ~5 minute guide to Numba](https://numba.readthedocs.io/en/stable/user/5minguide.html) |   |
| | Week 2: On-Premise Large-Scale CPU-computing with MPI | 4/4/2022 | An Introduction to Computing Clusters and CPU Hardware considerations | [Pacheco 2011](https://canvas.uchicago.edu/files/7194348/download?download_frd=1) (Ch. 1-2), [Midway User Guide](https://rcc.uchicago.edu/docs/) | |
| | | 4/6/2022 | Cluster Computing via Message Passing Interface (MPI) for Python | [Pacheco 2011](https://canvas.uchicago.edu/files/7194348/download?download_frd=1) (Ch. 3), [Dalcín et al. 2008](https://www-sciencedirect-com.proxy.uchicago.edu/science/article/pii/S0743731507001712?via%3Dihub) | |
| | Week 3: On-Premise GPU-computing | 4/11/2022 | An Introduction to GPUs and GPU Programming | [Scarpino 2012](https://canvas.uchicago.edu/files/7194342/download?download_frd=1) (Read Ch. 1, Skim Ch. 2-5,9) | |
| | | 4/13/2022 | Harnessing GPUs in Python | [Klöckner et al. 2012 "PyCUDA and PyOpenCL"](https://arxiv.org/pdf/0911.3456.pdf) | |
| Architecting Computational Social Science Data Solutions in the Cloud | Week 4: An Introduction to Cloud Computing and Cloud HPC Architectures | 4/18/2022 | Bursting HPC into the Cloud | [Jorissen and Bouffler 2017](https://canvas.uchicago.edu/files/7194340/download?download_frd=1) (Read Ch. 1, Skim Ch. 4-7), [Armbrust et al. 2009](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2009/EECS-2009-28.pdf), [Introduction to HPC on AWS](https://d1.awsstatic.com/whitepapers/Intro_to_HPC_on_AWS.pdf), [HPC Architectural Best Practices](https://d1.awsstatic.com/whitepapers/architecture/AWS-HPC-Lens.pdf) | |
| | | 4/20/2022 | An Introduction to Boto3 and Serverless HPC | [Jonas et al. 2019](https://arxiv.org/pdf/1902.03383.pdf), ["What is AWS Lambda"](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html), [Boto3 Documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html) | Due: Assignment 1 (11:59 PM) |
| | Week 5: Architecting Large-Scale Data Solutions in the Cloud | 4/25/2022 | "Data Lake" Architectures | [Data Lakes and Analytics on AWS](https://aws.amazon.com/big-data/datalakes-and-analytics/), [AWS Data Lake Whitepaper](https://d1.awsstatic.com/whitepapers/Storage/data-lake-on-aws.pdf), [*Introduction to AWS Boto in Python*](https://campus.datacamp.com/courses/introduction-to-aws-boto-in-python) (DataCamp Course; Practice working with S3 Data Lake in Python) | |
| | | 4/27/2022 | Large-Scale Database Solutions | ["Which Database to Use When?" (YouTube),](https://youtu.be/KWOSGVtHWqA) Optional: [Data Warehousing on AWS Whitepaper](https://d0.awsstatic.com/whitepapers/enterprise-data-warehousing-on-aws.pdf), [AWS Big Data Whitepaper](https://d1.awsstatic.com/whitepapers/Big_Data_Analytics_Options_on_AWS.pdf) | |
| | Week 6: Large-Scale Data Ingestion and Processing | 5/2/2022 | Event-Driven Ingestion and Processing | ["Scalable serverless event-driven architectures with SNS, SQS & Lambda" (YouTube)](https://www.youtube.com/watch?v=8zysQqxgj0I) <br/> Optional: ["Using Lambda with Amazon SQS"](https://docs.aws.amazon.com/lambda/latest/dg/with-sqs.html), ["Fanout to Amazon SQS Queues"](https://docs.aws.amazon.com/sns/latest/dg/sns-sqs-as-subscriber.html), ["Using AWS Lambda with Amazon S3"](https://docs.aws.amazon.com/lambda/latest/dg/with-s3.html) ||
| | | 5/4/2022 | Batch Processing with Apache Hadoop and MapReduce | [White 2015](https://canvas.uchicago.edu/files/7194355/download?download_frd=1) (read Ch. 1-2, Skim 3-4), [Dean and Ghemawat 2004](https://www.usenix.org/legacy/publications/library/proceedings/osdi04/tech/full_papers/dean/dean.pdf), ["What is Amazon EMR?"](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-what-is-emr.html), Running MapReduce Jobs with Python’s “mrjob” package on EMR ([Fundamentals](https://mrjob.readthedocs.io/en/latest/guides/quickstart.html) and [Elastic MapReduce Quickstart](https://mrjob.readthedocs.io/en/latest/guides/emr-quickstart.html)) | |
| High-Level Paradigms for Large-Scale Data Analysis, Prediction, and Presentation | Week 7: Spark | 5/9/2022 | Large-Scale Data Processing and Analysis with PySpark | [Karau et al. 2015](https://canvas.uchicago.edu/files/7194339/download?download_frd=1) (Read Ch. 1-4, Skim 9-11), [*Introduction to PySpark*](https://learn.datacamp.com/courses/introduction-to-pyspark) (DataCamp Course), Optional: Videos about accelerating Spark with GPUs (via [Horovod](https://www.youtube.com/watch?v=D1By2hy4Ecw) for deep learning, and the RAPIDS libraries for both [ETL and ML acceleration in Spark 3.0](https://www.youtube.com/watch?v=4MI_LYah900)) | |
| | | 5/11/2022 | A Deeper Dive into the PySpark Ecosystem | [*Machine Learning with PySpark*](https://campus.datacamp.com/courses/machine-learning-with-pyspark) (DataCamp Course), [Guller 2015](https://canvas.uchicago.edu/files/7194338/download?download_frd=1), [Hunter 2017](https://www.youtube.com/watch?v=NmbKst7ny5Q) (Spark Summit Talk), [GraphFrames Documentation for Python](https://docs.databricks.com/spark/latest/graph-analysis/graphframes/user-guide-python.html), [Spark NLP Documentation](https://nlp.johnsnowlabs.com/), Optional: [*Feature Engineering with PySpark*](https://learn.datacamp.com/courses/feature-engineering-with-pyspark) (DataCamp Course) | Due: Assignment 2 (11:59 PM) |
| | Week 8: Dask | 5/16/2022 | Introduction to Dask | [“Why Dask,”](https://docs.dask.org/en/latest/why.html) [Dask Slide Deck](https://dask.org/slides.html),  [*Parallel Programming with Dask*](https://learn.datacamp.com/courses/parallel-programming-with-dask-in-python) (DataCamp Course) | |
| | | 5/18/2022 | Accelerating Dask |  | |
| | Week 9: Presenting Data and Insights from Large-Scale Data Pipelines | 5/23/2022 | Building and Deploying (Scalable) Public APIs and Web Applications with Flask and AWS Elastic Beanstalk | Documentation for [Flask](https://flask-doc.readthedocs.io/en/latest/index.html), and [Elastic Beanstalk](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/Welcome.html) | |
|| | 5/25/2022 | Visualizing Large Data | Documentation for [DataShader](https://datashader.org/index.html) and [Bokeh](https://bokeh.org/), and integrating the two libraries using [HoloViews](http://holoviews.org/user_guide/Large_Data.html) |  |
|   |   | 5/27/2022  |  |   | Due: Assignment 3 (11:59 PM) |
| Student Projects | Week 10: Final Projects | 6/3/2022 ||| Due: Final Project + Presentation Video (11:59 PM) |

## Works Cited

"A ~5 minute guide to Numba." https://numba.readthedocs.io/en/stable/user/5minguide.html. Accessed 3/2021.

Armbrust, Michael, Fox, Armando, Griffith, Rean, Joseph, Anthony D., Katz, Randy H., Konwinski, Andrew, Lee, Gunho, Patterson, David A., Rabkin, Ariel, Stoica, Ion, and Matei Zaharia. 2009. "Above the Clouds: A Berkeley View of Cloud Computing." Technical report, EECS Department, University of California, Berkeley.

["AWS Big Data Analytics Options on AWS." December 2018.)](https://d1.awsstatic.com/whitepapers/Big_Data_Analytics_Options_on_AWS.pdf) AWS Whitepaper.

"AWS Elastic Beanstalk Developer Guide." https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/Welcome.html. Accessed 3/2021.

["Building Big Data Storage Solutions (Data Lakes) for Maximum Flexibility." July 2017.](https://d1.awsstatic.com/whitepapers/Storage/data-lake-on-aws.pdf)

Dalcín, Lisandro, Paz, Rodrigo, Storti, Mario, and Jorge D'Elía. 2008. "MPI for Python: Performance improvements and MPI-2 extensions." *J. Parallel Distrib. Comput.* 68: 655-662.

["Data Warehousing on AWS." March 2016.](https://d0.awsstatic.com/whitepapers/enterprise-data-warehousing-on-aws.pdf) AWS Whitepaper.

"DataShader Documentation." https://datashader.org/index.html. Accessed 3/2021.

Dean, Jeffrey, and Sanjay Ghemawat. 2004. "MapReduce: Simplified data processing on large clusters." In *Proceedings of Operating Systems Design and Implementation (OSDI)*. San Francisco, CA. 137-150.

Evans, Robert and Jason Lowe. "Deep Dive into GPU Support in Apache Spark 3.x." https://www.youtube.com/watch?v=4MI_LYah900. Accessed 3/2021.

"Fanout to Amazon SQS queues." https://docs.aws.amazon.com/sns/latest/dg/sns-sqs-as-subscriber.html. Accessed 3/2022.

"Faster code via static typing." http://docs.cython.org/en/latest/src/quickstart/cythonize.html. Accessed 3/2021

*Feature Engineering with PySpark*. https://learn.datacamp.com/courses/feature-engineering-with-pyspark. Accessed 3/2020.

"Flask Documentation." https://flask-doc.readthedocs.io/en/latest/index.html. Accessed 3/2021.

"GraphFrames user guide - Python." https://docs.databricks.com/spark/latest/graph-analysis/graphframes/user-guide-python.html. Accessed 3/2020.

Guller, Mohammed. 2015. "Graph Processing with Spark." In *Big Data Analytics with Spark*. New York: Apress.

["High Performance Computing Lens AWS Well-Architected Framework." December 2019.](https://d1.awsstatic.com/whitepapers/architecture/AWS-HPC-Lens.pdf) AWS Whitepaper.

Hunter, Tim. October 26, 2017. "GraphFrames: Scaling Web-Scale Graph Analytics with Apache Spark." https://www.youtube.com/watch?v=NmbKst7ny5Q.

*Introduction to AWS Boto in Python*. https://campus.datacamp.com/courses/introduction-to-aws-boto-in-python. Accessed 3/2020.

["Introduction to HPC on AWS." n.d.](https://d1.awsstatic.com/whitepapers/Intro_to_HPC_on_AWS.pdf) AWS Whitepaper.

*Introduction to PySpark*. https://learn.datacamp.com/courses/introduction-to-pyspark. Accessed 3/2020.

Jonas, Eric, Schleier-Smith, Johann, Sreekanti, Vikram, and Chia-Che Tsai. 2019. "Cloud Programming Simplified: A Berkeley View on Serverless Computing." Technical report, EECS Department, University of California, Berkeley.

Jorissen, Kevin, and Brendan Bouffler. 2017. *AWS Research Cloud Program: Researcher's Handbook*. Amazon Web Services.

Karau, Holden, Konwinski, Andy, Wendell, Patrick, and Matei Zaharia. 2015. *Learning Spark*. Sebastopol, CA: O'Reilly.

Klöckner, Andreas, Pinto, Nicolas, Lee, Yunsup, Catanzaro, Bryan, Ivanov, Paul, and Ahmed Fasih. 2012. "PyCUDA and PyOpenCL: A Scripting-Based Approach to GPU Run-Time Code Generation." *Parallel Computing* 38(3): 157-174.

*Machine Learning with PySpark*. https://campus.datacamp.com/courses/machine-learning-with-pyspark. Accessed 3/2020.

"mrjob v0.7.1 documentation." https://mrjob.readthedocs.io/en/latest/index.html. Accessed 3/2020.

Pacheco, Peter. 2011. *An Introduction to Parallel Programming*. Burlington, MA: Morgan Kaufmann.

*Parallel Programming with Dask*. https://learn.datacamp.com/courses/parallel-programming-with-dask-in-python. Accessed 3/2020.

Petrossian, Tony, and Ian Meyers. November 30, 2017. "Which Database to Use When?" https://youtu.be/KWOSGVtHWqA. AWS re:Invent 2017.

Pirtle, Justin. December 8, 2020. "Scalable serverless event-driven architectures with SNS, SQS, and Lambda." https://www.youtube.com/watch?v=8zysQqxgj0I. AWS re:Invent 2020.

"RCC User Guide." rcc.uchicago.edu/docs/. Accessed March 2020.

Robey, Robert and Yuliana Zamora. 2021. *Parallel and High Performance Computing*. Shelter Island, NY: Manning.

Scarpino, Matthew. 2012. *OpenCL in Action*. Shelter Island, NY: Manning.

Sergeev, Alex. March 28, 2019. "Distributed Deep Learning with Horovod." https://www.youtube.com/watch?v=D1By2hy4Ecw.

"Spark NLP Documentation." https://nlp.johnsnowlabs.com/. Accessed 3/2021.

"The Bokeh Visualization Library Documentation." https://bokeh.org/. Accessed 3/2021.

"Using AWS Lambda with S3." https://docs.aws.amazon.com/lambda/latest/dg/with-s3.html. Accessed 3/2022.

"Using Lambda with Amazon SQS." https://docs.aws.amazon.com/lambda/latest/dg/with-sqs.html. Accessed 3/2022.

"What is Amazon EMR." https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-what-is-emr.html. Accessed 3/2020.

"What is AWS Lambda?" https://docs.aws.amazon.com/lambda/latest/dg/welcome.html. Accessed 3/2022.

White, Tom. 2015. *Hadoop: The Definitive Guide*. Sebastopol, CA: O'Reilly.

"Why Dask." https://docs.dask.org/en/latest/why.html. Accessed 3/2020.

"Working with large data using datashader." http://holoviews.org/user_guide/Large_Data.html. Accessed 3/2021.
