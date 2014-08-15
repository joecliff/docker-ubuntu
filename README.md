## Ubuntu Dockerfile


Forked from [dockerfile/ubuntu]](https://github.com/dockerfile/ubuntu). Reduce the size by removing some packages.


### Installation

1. Install [Docker](https://www.docker.io/).

2. Download from public [Docker Registry](https://index.docker.io/): `docker pull joecliff/docker-ubuntu`

   (alternatively, you can build an image from Dockerfile: `docker build -t="joecliff/docker-ubuntu" github.com/joecliff/docker-ubuntu`)


### Usage

    docker run -it --rm joecliff/docker-ubuntu
