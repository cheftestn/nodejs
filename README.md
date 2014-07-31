## Node.js Dockerfile

This repository contains Dockerfile of Node.js for Docker's trusted build published to the public Docker Registry.
Dependencies

    dockerfile/python

### Installation

    Install Docker.

    Download trusted build from public Docker Registry: docker pull dockerfile/nodejs

    (alternatively, you can build an image from Dockerfile: docker build -t="dockerfile/nodejs" github.com/dockerfile/nodejs)

#### Usage

docker run -it --rm dockerfile/nodejs

Run node

docker run -it --rm dockerfile/nodejs node

Run npm

docker run -it --rm dockerfile/nodejs npm
