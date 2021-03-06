# Nuvo Data Science Quickstart

Nuvo's Data Science Architecture is an opinionated IOT architecture developed on Docker to be easily provisioned, managed, and scaled. The Nuvo Quickstart can help you get up and running quickly.

Data is ingested through Kafka and processed online using Spark Streaming. Data is also immediately saved to HDFS from Kafka and archived in S3 for offline batch jobs and data backup. Across the organization, all event data is stored in [Avro](http://avro.apache.org/docs/current/) format.

![Nuvo Data Science Architecture](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/98bba24c-fff7-4b01-a90b-7761c2c50641/screenshot.png?AWSAccessKeyId=AKIAJLJXUMP5IHUZAPFQ&Expires=1534117786&Signature=eFEOmpktuPQeEZq46VDYdX27%2BMI%3D)

## Getting Started
```git clone https://github.com/NuvoHome/nuvo-data-science-quickstart
cd nuvo-data-science-quickstart
sudo docker-compose up -d
```
