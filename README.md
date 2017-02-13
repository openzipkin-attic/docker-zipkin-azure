[![Build Status](https://travis-ci.org/openzipkin/docker-zipkin-azure.svg)](https://travis-ci.org/openzipkin/docker-zipkin-azure)
[![zipkin-azure](https://quay.io/repository/openzipkin/zipkin-azure/status "zipkin-azure")](https://quay.io/repository/openzipkin/zipkin-azure)

# docker-zipkin-azure

This repository contains the Docker build definition and release process for
[openzipkin/zipkin-azure](https://github.com/openzipkin/zipkin-azure).

This layers Microsoft Azure support on the base [zipkin docker image](https://github.com/openzipkin/docker-zipkin).

Currently, this adds Event Hub Collector support

## Running

TODO: link to variables used and show docker run -e for the minimum needed

## Configuration

Configuration is via environment variables, defined by [zipkin-azure](https://github.com/openzipkin/zipkin-azure/blob/master/README.md).

In docker, the following can also be set:

    * `JAVA_OPTS`: Use to set java arguments, such as heap size or trust store location.

### Event Hub

Event Hub Configuration variables are detailed [here](https://github.com/openzipkin/zipkin-azure/tree/master/collector/eventhub).
