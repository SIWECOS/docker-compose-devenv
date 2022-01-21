# docker-compose-devenv

To start a local SIWECOS setup on your machine, install Docker and docker-compose,
clone this repo and run `docker-compose up` inside the repo's directory.

**NB: In most cases you don't need to use this repo!**<br>
Just use the hosted variant on https://siwecos.de or use the [SIWECOS/docker-compose-scanners]() for hosting the core functionality of SIWECOS by yourself.

## Usage with local development copies of services
You have to choices here:
* a) you do your local changes, build a local container and update the image name in this repos's docker-compose.yml
* b) you mount your local copy of the code as a volume of the corresponding container of this repo's docker-compose.yml