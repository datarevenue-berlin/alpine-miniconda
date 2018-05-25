[![](https://images.microbadger.com/badges/image/drtools/alpine-miniconda.svg)](https://hub.docker.com/r/drtools/alpine-miniconda/)
# Alpine Miniconda

Safe Miniconda install in an Alpine Linux container.
This image intend to be used as a base image, smaller than the official Continiuum image, based on Ubuntu.

The official Miniconda image [weigth 158MB](https://microbadger.com/images/continuumio/miniconda) and this one [only 57MB](https://microbadger.com/images/drtools/alpine-miniconda).


A special user is create with uid 1000 and can be use with any public user without security breach.

# Changelog
## 4.5.1 
- Updated Miniconda version to 4.5.1
- Set conda-forge as top prio channel

# Usage

You can download and run this image with these commands:

```
docker pull drtools/alpine-miniconda
docker run -i -t drtools/alpine-miniconda /bin/bash
```

This image is a modified version of [show0k/alpine-miniconda](https://github.com/show0k/alpine-jupyter-docker) image modified to suite the companies needs.
