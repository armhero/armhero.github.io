--- 
title: "ARMhero"
---
Some convenient [Docker](http//docker.com) images for the ARM platform, built on the Raspberry Pi.

## Base images

The base images include only the operating system itself, nothing other. They are built automatically with Jenkins CI. The jobs are defined in Jenkins DSL as found in the [armhero/jenkins-dsl](https://github.com/armhero/jenkins-dsl) repository.

### Alpine Linux - [armhero/alpine](https://github.com/armhero/alpine)

A small and secure Linux distribution. Only 3 MB.

[View on GitHub](https://github.com/armhero/alpine) | [View on Docker Hub](https://hub.ocker.com/r/armhero/alpine/)

### Debian Linux - [armhero/debian](https://github.com/armhero/debian)

A popular Linux distribution.

[View on GitHub](https//github.com/armhero/debian) | [View on Docker Hub](https//hub.ocker.com/r/armhero/debian/)

## About

These images are built with Jenkins on a Raspberry Pi 1, 2 and 3 Cluster. They are created on a regular basis, stable branches once a week, testing branches every night.
