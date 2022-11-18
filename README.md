## Introduction
* Hello there 👋, I’m Tonny-Bright. I worked as a Lead Operations Engineer at Dreamoval, a Freelancer and a data science enthusiast. Python is my language of choice for most things. 

* I’m a certified AWS Solutions Architect Associate and have worked as a Cloud Support Engineer for three and half years. In those years, I have worked mainly with AWS services ranging from EC2, VPC, ECS, Aurora, DMS, S3, etc. 
* Other tools and services apart from AWS includes Datadog, Metabase for Business Intelligence dashboarding and analysis, Elasticsearch, Kibana, Apache kafka, Microservices Architecture, MongoDB, MySQL, Redis, Python, etc. 

* I’m looking to collaborate on anything relating to Data; data pipelines, data warehouses, data lakes, delta lake, data analysis, machine learning.

## Projects
* [Data Pipeline](https://github.com/TMCreme/dbt_airflow_project) using Apache Airflow and DBT deployed on AWS ECS. The aim was simulate a real world scenario of data ingestion, transformation, persisting and analysis. Airflow handles the orchestration hence the ingestion was implemented in custom python code with Airflow operators and tasks. With the file sensors in Airflow, this can be extended for streaming for data files. Transformations are handled in Data Build Tool (DBT) and stored in PostgreSQL. By use of a Jenkinsfile, the project is build successfully for deployment and stored on Dockerhub.

* [Data Streaming](https://github.com/TMCreme/twitter-sentiments-pyspark) using PySpark, Apache Kafka and Tweepy. The streaming projects aims to simulate realtime data streaming and analysis on the fly. The Tweepy package allows us to access tweets based on specific parameters. The tweets are streamed onto a kafka topic, on which by the help of PySpark Structured Streaming, a listener is available for any data arriving. The data is aggregated, transformed and a plot generated for viewing. 

* [LawSMS](https://isms.lawsms.com/). A mobile and web application to deliver legal content through SMS subscriptions. Using Django and Django Rest Framework for APIs to be consumed by the mobile and web applications

* Other projects including APIs in django are available in the repository.  

- 📫 Reach me at tonnybright35@gmail.com or @BrightTonny on Twitter. 


<!---
TMCreme/TMCreme is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
