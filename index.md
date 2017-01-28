Some convenient [Docker](http://docker.com) images for the ARM Platform, built on the Raspberry Pi.

## Base images

The base images include only the operating system itself, nothing other. They are built automatically with Jenkins CI. The Jobs are defined in Jenkins DSL found in the [armhero/jenkins-dsl](https://github.com/armhero/jenkins-dsl) repository.

### Alpine Linux: armhero/alpine

A small and secure distribution. Only 3MB.

[View on Github](https://github.com/armhero/alpine) | [View on Docker Hub](https://hub.docker.com/r/armhero/debian/)

## About

These images are built with Jenkins on a Raspberry Pi 1, 2 and 3 Cluster. They are created on a regular basis, stable branches once a week, testing branches all night.
