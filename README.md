# Supported tags and respective `Dockerfile` links

-	[`latest` (*Dockerfile*)](https://github.com/CharmingSteve/nginx-webdav-container/blob/master/Dockerfile)

[![](https://hub.docker.com/repository/docker/charmingsteve/nginxwebdav)](https://hub.docker.com/repository/docker/charmingsteve/nginxwebdav )

# How to use this image
Edit the docker-compose.yaml file, change the volume source to match your system.
You can also password protect by uncommenting the lines for  `USERNAME` and `PASSWORD`
 

```console
$ docker compose up -d
```
This will build and start a webdav server listening on the default port of 80.
Then access it via `http://localhost:80` or `http://host:80` in a browser.

This server will serve files located in your /media folder

Image's supported volumes:
- `/media` - served directory


# Supported Docker versions

This image is officially supported on Docker version 1.10.2.
Support for older versions (down to 1.6) is provided on a best-effort basis.
Please see [the Docker installation documentation](https://docs.docker.com/installation/) for details on how to upgrade your Docker daemon.
