FROM biocontainers/biocontainers:debian-stretch-backports
MAINTAINER biocontainers <biodocker@gmail.com>
LABEL    software="python3-burrito" \ 
    container="python3-burrito" \ 
    about.summary="Python 3 framework for wrapping and controlling command-line applications" \ 
    about.home="https://github.com/biocore/burrito" \ 
    software.version="0.9.1-1-deb" \ 
    version="1" \ 
    about.copyright="2014-2015 burrito development team <gregcaporaso@gmail.com>" \ 
    about.license="BSD-3-clause" \ 
    about.license_file="/usr/share/doc/python3-burrito/copyright" \ 
    about.tags=""

ENV DEBIAN_FRONTEND noninteractive
RUN apt-get update && apt-get install -y python3-burrito && apt-get clean && apt-get purge && rm -rf /var/lib/apt/lists/* /tmp/*
USER biodocker
