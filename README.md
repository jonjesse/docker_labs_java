# Tutorial: Debugging Java Applications in Docker

NOTICE: This code already has the rot13 password workaround fixed.

Build with docker-compose:
```
docker-compose build
```
Start app with docker-compose:
```
docker-compose up -d
```

Start app with docker stack:
```
docker stack deploy -c docker-stack.yml java
```


Java developers can use Docker to build a development environment where they can run, test, and live debug code running within a container. Debugging a node.js application was demonstrated at DockerCon 2016 showing that development using containers can be performed on many platforms using other programming languages.





This tutorial includes Docker images and an application for Java development using containers. An examples for Eclipse, IntelliJ CE, and Netbeans are provided.

* [Eclipse](Eclipse-README.md)
* [IntelliJ](IntelliJ-README.md)
* [NetBeans](NetBeans-README.md)

Before starting the tutorial, please have [Docker](https://www.docker.com/products/overview) installed.
