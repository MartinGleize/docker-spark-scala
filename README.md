![Docker Pulls](https://img.shields.io/docker/pulls/mgleize/spark-scala)

# docker-spark-scala
A minimal Docker image with Apache Spark, Scala and SBT, to test Spark applications.

Can also be accessed through Docker Hub: `docker pull mgleize/spark-scala`

## Requirements

Docker

## Build

`docker build -t spark-scala .`

## Test

`docker run -it --rm spark-scala bin/run-example SparkPi 10`
