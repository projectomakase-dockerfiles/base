# Base Project Omakase Docker Image#

This repository contains the base image that is used to build the portfolio of Project Omakase Docker images.

### Base image ###

This image is used as a base image for all Project Omakase images. It provides a base layer that includes:


1. A `omakase` user (uid/gid `1001`) with home directory set to `/var/omakase`
2. A few tools that may be useful when extending the image or installing software, like `unzip`.

### Operating system

This image uses Debian 8.

### Working directory

This image has the working directory set to `/var/omakase`, which is the `omakase` user home directory at the same time.

### Availability

The `Dockerfile` is available in the `master` branch and is built in the Docker HUB as `projectomakase/base:latest`.

