> ⚠️ **This project is no longer maintained.** Please use the [Kubernetes deployer](https://dataflow.spring.io/docs/installation/kubernetes/) as there is no longer a reason to maintain an OpenShift specific deployer.

# Spring Cloud Data Flow Server for OpenShift  [![Build Status](https://travis-ci.org/donovanmuller/spring-cloud-dataflow-server-openshift.svg?branch=master)](https://travis-ci.org/donovanmuller/spring-cloud-dataflow-server-openshift) [![codecov](https://codecov.io/gh/donovanmuller/spring-cloud-dataflow-server-openshift/branch/master/graph/badge.svg)](https://codecov.io/gh/donovanmuller/spring-cloud-dataflow-server-openshift)

This project provides a Spring Cloud Data Flow server for deployments to OpenShift 3, using the 
[Spring Cloud Deployer OpenShift](https://github.com/donovanmuller/spring-cloud-deployer-openshift) 
implementation of the [Spring Cloud Deployer](https://github.com/spring-cloud/spring-cloud-deployer) SPI.

Please refer to the [reference documentation](https://donovanmuller.github.io/spring-cloud-dataflow-server-openshift/docs/1.1.0.RELEASE/reference/htmlsingle) on how to get started.

## Building

Clone the repo and type 

```console
$ ./mvnw clean install 
```

To build the docker image for the Data Flow Server

```console
$ ./mvnw package docker:build -pl :spring-cloud-dataflow-server-openshift
```

## Further Reading

Please see the following posts for more information:

* [Spring Cloud Deployer OpenShift](http://blog.switchbit.io/spring-cloud-deployer-openshift)
* [SCDF OpenShift: Deploying Maven artifacts with custom Dockerfile](http://blog.switchbit.io/scdf-openshift-deploying-maven-artifacts-with-custom-dockerfile)
