# gcp_learning_log
Learning Log for the GCP data Engineer Certification 

# Professional Data Engineer
A Professional Data Engineer enables data-driven decision making by collecting, transforming, and publishing data. A Data Engineer should be able to design, build, operationalize, secure, and monitor data processing systems with a particular emphasis on security and compliance; scalability and efficiency; reliability and fidelity; and flexibility and portability. A Data Engineer should also be able to leverage, deploy, and continuously train pre-existing machine learning models.

https://cloud.google.com/certification/data-engineer


Data Engineer learning path
Data Engineers design solutions that ensure maximum flexibility and scalability, while meeting all required security controls.

Products
What you'll learn
BigQuery, Dataflow, Data Fusion, Cloud Composer, BigQuery ML, IoT, TensorFlow, Dataproc, workload migration

Courses
4

Labs
31

# Dataflow 

At Measurelab we’re currently at midst a project where we’re using more and more of the Google Cloud Platform tools. One that we’re currently using is Dataflow. 

Dataflow is a Pipeline serverless data processing workflow tool. The reason for using Dataflow over python based cloud functions is the scale of the data we’re working with is currently unknown. 

The horizontal scalability of the Dataflow means that our Workflow will scale between steps to better and more efficiently deal with the data we’re providing. 

Another reason why Dataflow was chosen is because it doesn’t wait for a previous step to finish before starting a new one, as long as there is no dependency. This is important for large scale jobs like the one we’re currently working on. 

The way I like to picture Dataflow working is like a beam of particles, small subsets of your data passing through the pipeline, and this is how I remember how Dataflow works, and that it’s based on Apache Beam. And since Dataflow is Apache Beam it means that Dataproc is Spark based. Which comes up a lot in the Data engineering GCP cert.


Documents by Juan Calvo: 
https://miro.com/app/board/o9J_kia5jmU=/

In interface, 
Create Job from template 
Notebooks - Building Apache Beam with Python in Notebooks. 

## Google Cloud Platform Big Data and Machine Learning Fundamentals 










