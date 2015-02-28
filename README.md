## Node.js Dockerfile


This repository contains **Dockerfile** of [Node.js](http://nodejs.org/) for [Docker](https://www.docker.com/)'s (https://registry.hub.docker.com/u/mikeholczer/docker-armhf-nodejs/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/). I would have made it an automated build, but it seems that armhf architectures aren't supported.


### Base Docker Image

* [mikeholczer/python](https://registry.hub.docker.com/u/mikeholczer/debian/)


### Installation

1. Install [Docker](https://www.docker.com/). (I need to provide more detail about getting it running on raspberry pi 2)

2. Download [automated build](https://registry.hub.docker.com/u/dockerfile/nodejs/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull mikeholczer/docker-armhf-nodejs`



### Usage

    docker run -it --rm mikeholczer/docker-armhf-nodejs

#### Run `node`

    docker run -it --rm mikeholczer/docker-armhf-nodejs node

#### Run `npm`

    docker run -it --rm mikeholczer/docker-armhf-nodejs npm
