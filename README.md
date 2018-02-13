<!-- [![Build Status](https://travis-ci.org/kaelzhang/docker-nginx.svg?branch=master)](https://travis-ci.org/kaelzhang/docker-nginx) -->
[![docker](https://img.shields.io/badge/docker-kaelz%2Fnginx-brightgreen.svg)](https://hub.docker.com/r/kaelz/nginx/)

# docker: kaelz/nginx

The altered nginx docker image from the official one, which includes [headers-more-nginx-module](https://github.com/openresty/headers-more-nginx-module)

Only supports `alpine` for now.

## Usage

```sh
docker pull kaelz/nginx:alpine
docker run -d -P --name nginx kaelz/nginx:alpine
```

****

This is the Git repo of the official Docker image for [nginx](https://registry.hub.docker.com/_/nginx/). See the
Hub page for the full readme on how to use the Docker image and for information
regarding contributing and issues.

The full readme is generated over in [docker-library/docs](https://github.com/docker-library/docs),
specificially in [docker-library/docs/nginx](https://github.com/docker-library/docs/tree/master/nginx).
