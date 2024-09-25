# Using Spark & Kafka
## About 

These notes were put together to help my fellow Kubrick Consultants master the syntax of PySpark & Kafka, the Python packages we use to compute in Databricks.

Unfortunately, I was laid off before I had the opportunity to share these techniques with my fellow consultants. Unfortunately, I was laid off before I had the opportunity to finish this repository as a company resource. Instead, I've opted to share a scrubbed version publicly, under the MIT license, to display my command of Spark and Kafka as tools.

## Layout & Use:

This project is broken up into two sub-folders, one for each package we used with Databricks, Spark & Kafka.

- Kafka Practice Streams
- Spark Practice Exercises

Within each folder, there are a set of techniques on display across a number of excercises. (Data Ingestion for Spark and Data Streaming for Kafka).

## Setup & Installation:

<b>Run these notebooks in Databricks (preferred method)</b>

In order to run these as production scripts, we'd want to use a cluster compute tool like Amazon Redshift or Databricks. Those are a bit of a pain to get running, so I'm using Jupyter notebooks for now.

In order to display the intended result of the code, I've uploaded the exercise solutions as Jupyter notebooks. Such notebooks allowed me to keep detailed notes during the learning process. To test the functionality of the code in the notebooks, you can start a databricks 2-core cluster with a free trial and drop these notebooks into your enviornment with the GUI.

These exercises were adaptations of former client problems solved by senior staff at Kubrick Group. They shared their solutions with us in a classroom context, asking us to cross gaps in efficiency, solve similar problems to common requests they encountered, and generally get comofortable with building and using dataframes in a cluster compute context.

## Documentation

<b> Apache Spark Documentation </b>

Apache's website also has documentation available here:
https://spark.apache.org/docs/latest/

Installation and update notes can be found here:

https://spark.apache.org/docs/latest/api/python/getting_started/install.html

<b> Kafka: The Definitive Guide </b>

Download the Kafka ebook from Confluent.io (a cloud-hosted Kafka application)
https://www.confluent.io/resources/kafka-the-definitive-guide/

<b> Databricks Academy </b>
https://partner-academy.databricks.com/learn
