# Using Spark & Kafka
## About 

These notes were put together to help my fellow Kubrick Consultants master the syntax of PySpark & Kafka, the Python packages we use to compute in Databricks.

Unfortunately, I was laid off before I had the opportunity to share these techniques with my fellow consultants. Unfortunately, I was laid off before I had the opportunity to finish this repository as a company resource. Instead, I've opted to share a scrubbed version publicly, under the MIT license, to display my command of Spark and Kafka as tools.

## Layout & Use:

This folder is broken up into several sub-folders. 

Spark & Kafka are each given their own folder. Each subject requires different installs and methods. 

Within each subject folder, there are techniques, excercises, and an example of a Data Workflow. (Data Ingestion for Spark and Data Streaming for Kafka).

- Spark
  - Techniques
  - Excercises
  - Data Ingestion
- Kafka
  - Techniques
  - Excercises
  - Data Streaming

Techniques provide the building blocks for the skills required to use each package. The excercises, which are completed with code from David Portas, allow consultants to apply their understanding. <i><u>(We might want to consider making blank versions of these excercises as notebooks)</i></u>

The Data Workflow samples are collections of relevant files using the corresponding package to solve a business challenge. (The Spark one needs some work)

## Setup & Installation:

<b>Run these notebooks in Databricks (preferred method)</b>

Click the "+ New" or "Create" button. Upload this folder to your Databricks enviornment. Done!

If you have access to the GitLab address for this repository, you can also sync via the https link.

<b>Running Parallel Machines Locally</b>

To run this code locally, we will need to mimic the functionality of a parallel computing enviornment like Databricks. This requires several local installs.
- Spark
- PySpark
- Kafka
- Kafka Admin

https://www.knowledgehut.com/blog/big-data/how-to-install-apache-spark-on-windows
<u><i> This link is for Spark -- I need to actually figure out how to do this, still. Also, I have no idea how to that with Kafka.</i></u>

## Documentation

You can also refer to the original documentation used to teach Spark here:

<b>Internal Kubrick Documentation</b>

(Intro to Spark, Kafka and Databricks)

https://kubrickgroup.sharepoint.com/:u:/r/sites/HQHUB/SitePages/Introduction-to-Spark.aspx?csf=1&web=1&e=IZ24bv


<b> Apache Spark Documentation </b>

Apache's website also has documentation available here:
https://spark.apache.org/docs/latest/

Installation and update notes can be found here:

https://spark.apache.org/docs/latest/api/python/getting_started/install.html

<b> Kafka: The Definitive Guide </b>

Download the Kafka ebook from Confluent.io (a cloud-hosted Kafka application)
https://www.confluent.io/resources/kafka-the-definitive-guide/

https://partner-academy.databricks.com/learn
