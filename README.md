# Docker Hub

[![Build Status](https://img.shields.io/github/workflow/status/lade-io/docker-hub/Mirror.svg)](https://github.com/lade-io/docker-hub/actions?workflow=Mirror)

This is a [Docker Hub](https://hub.docker.com) mirror hosted by [Github Pages](https://pages.github.com).

## Usage

List all Golang tags:

```sh
$ curl https://hub.lade.io/v2/library/golang/tags/list
{
  "name": "library/golang",
  "tags: [
    <tag>,
    ...
  ]
}
```
