# OC From Scratch
This repo contains the resources to setup your own OpenChirp instance
from scratch.
We will walk through a typical install on Debian.

# Steps

## Install Software Dependencies

### Setup additional Debian sources
Add `nodesource.list` file to `/etc/apt/source.list.d/` with the
following contents:

```
# Supports OpenChirp V1.0
deb https://deb.nodesource.com/node_10.x stretch main
deb-src https://deb.nodesource.com/node_10.x stretch main
```

### Install the `openchirp-dep` packge

## Setup Apache2 for website and rest

## Build Website

## Build Config REST server

## Setup Systemd for REST server
