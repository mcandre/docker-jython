# docker-jython - a Docker container having Jython

# DOCKER HUB

https://registry.hub.docker.com/u/mcandre/docker-jython/

# EXAMPLE

```
$ make
docker run --rm mcandre/docker-jython:latest jython --version
Jython 2.7.0
docker run --rm mcandre/docker-jython:latest java -version
java version "1.8.0_51"
Java(TM) SE Runtime Environment (build 1.8.0_51-b16)
Java HotSpot(TM) 64-Bit Server VM (build 25.51-b03, mixed mode)
```

# REQUIREMENTS

* [Docker](https://www.docker.com/)

## Optional

* [make](http://www.gnu.org/software/make/)
* [Node.js](https://nodejs.org/en/) (for dockerlint)
