# Docker samba

Dockerhub link: [https://hub.docker.com/r/tothlp/samba](https://hub.docker.com/r/tothlp/samba)

## About this repository

This repository hosts the Dockerfile for an Alpine (3.18.4) based image, with the latest available samba client installed.

## Usage

Same as for any other Alpine-based images. The entry point is the default terminal. The entry point is the default terminal. The following example runs the container with invoking smbclient.

```bash
docker run --rm tothlp/samba:latest smbclient
```