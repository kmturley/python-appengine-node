# python-appengine-node

Docker image for sites which need to run:

* Python 2.7
* Google Cloud SDK (latest)
* Open JDK 8
* NodeJS 8.x
* Chrome

## Installation

    docker build -t "kmturley:python-appengine-node" .

## Usage

Within your own Dockerfile:

    FROM: kmturley/python-appengine-node

Within a CI pipeline:

    image: kmturley/python-appengine-node

## Contact

For more information please contact kmturley
