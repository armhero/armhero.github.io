---
title: "ARMhero"
---
Some convenient [Docker](http://docker.com) images for the ARM platform, built on the Raspberry Pi.

## Base images

The base images include only the operating system itself, nothing other. They are built automatically with Jenkins CI. The jobs are defined in Jenkins DSL as found in the [armhero/jenkins-dsl](https://github.com/armhero/jenkins-dsl) repository.

### Alpine Linux - [armhero/alpine](https://github.com/armhero/alpine)

A small and secure Linux distribution. Only 3 MB.

[View on GitHub](https://github.com/armhero/alpine) | [View on Docker Hub](https://hub.docker.com/r/armhero/alpine/)

### Raspbian Linux - [armhero/raspbian](https://github.com/armhero/raspbian)

Debian Linux for the Raspberry Pi.

*Works also on Raspberry Pi 1 and Zero.*

[View on GitHub](https://github.com/armhero/raspbian) | [View on Docker Hub](https://hub.docker.com/r/armhero/raspbian/)

### Debian Linux - [armhero/debian](https://github.com/armhero/debian)

A popular Linux distribution.

*Does only work on Raspberry 2 and above due lack of armv6 support.*

[View on GitHub](https://github.com/armhero/debian) | [View on Docker Hub](https://hub.docker.com/r/armhero/debian/)

## Application images

These images are built with Jenkins Pipeline. Refer to the Jenkinsfile if you want to know how it's built.

### Nextcloud - [armhero/nextcloud](https://github.com/armhero/nextcloud)

[Nextcloud](http://nextcloud.com) on ARM.

Usage:
```
docker run -d --name nextcloud -p 80:80 -v my_local_data_folder:/data armhero/nextcloud
```

[View on GitHub](https://github.com/armhero/nextcloud) | [View on Docker Hub](https://hub.docker.com/r/armhero/nextcloud/)

### Jenkins Slave - [armhero/jenkins-slave](https://github.com/armhero/jenkins-slave)

The Jenkins slave used to build these images.

Usage:
```
docker run -d --privileged -v /var/run/docker.sock:/var/run/docker.sock armhero/jenkins-slave
```

[View on GitHub](https://github.com/armhero/jenkins-slave) | [View on Docker Hub](https://hub.docker.com/r/armhero/jenkins-slave/)

## About

These images are built with Jenkins on a Raspberry Pi 1, 2 and 3 Cluster. They are created on a regular basis, stable branches once a week, testing branches every night.
