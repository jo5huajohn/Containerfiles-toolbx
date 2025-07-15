# Containerfiles-toolbx

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

