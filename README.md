# Containerfiles-toolbx

[![Build toolbx images](https://github.com/jo5huajohn/Containerfiles-toolbx/actions/workflows/main.yml/badge.svg)](https://github.com/jo5huajohn/Containerfiles-toolbx/actions/workflows/main.yml)

Containerfiles for toolbx images

## Build

```shell
podman build \
    --squash \
    --tag localhost/fedora-base:42 \
    /path-to-Containerfile-dir
```

## Running

```shell
toolbox create -i localhost/fedora-base:42 fedora-42-base
```

