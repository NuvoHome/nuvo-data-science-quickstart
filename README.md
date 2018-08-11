# Nuvo Data Science Quickstart

Nuvo's Data Science Architecture is an opinionated IOT architecture developed on Docker to be easily provisioned, managed, and scaled. The Nuvo Quickstart can help you get up and running quickly.

Data is ingested through Kafka and processed online using Spark Streaming. Data is also immediately saved to HDFS from Kafka and archived in S3 for offline batch jobs and data backup. Across the organization, all event data is stored in [Avro](http://avro.apache.org/docs/current/) format.

![Nuvo Data Science Architecture](https://www.notion.so/nuvo/System-Architecture-fa8ff764b2c845aebf2eb12a76f05b0b#d4e6bdc7f7014d35af744c8d1fee77bb)

## Getting Started
```git clone https://github.com/NuvoHome/nuvo-data-science-quickstart
cd nuvo-data-science-quickstart
sudo docker-compose up -d
```
