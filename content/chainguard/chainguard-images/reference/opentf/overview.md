---
title: "Image Overview: opentf"
type: "article"
description: "Overview: opentf Chainguard Image"
date: 2022-11-01T11:07:52+02:00
lastmod: 2022-11-01T11:07:52+02:00
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
menu:
  docs:
    parent: "images-reference"
weight: 500
toc: true
---

[cgr.dev/chainguard/opentf](https://github.com/chainguard-images/images/tree/main/images/opentf)

| Tag (s)       | Last Changed  | Digest                                                                    |
|---------------|---------------|---------------------------------------------------------------------------|
|  `latest`     | September 8th | `sha256:8437c2482c1fc35677bf1d0227c078f183451c9949b04be80c9653f0ea9d5f8f` |
|  `latest-dev` | September 8th | `sha256:36139a6cd25ee630ca2492741f95420d27dc7d2dad80874306f075187f222367` |



[OpenTF](https://github.com/opentffoundation/opentf) lets you declaratively manage your cloud infrastructure.


## Get It!

The image is available on `cgr.dev`:

```
docker pull cgr.dev/chainguard/opentf
```

The image sets `opentf` as the entrypoint. To run it:

```
Usage: opentf [global options] <subcommand> [args]

The available commands for execution are listed below.
The primary workflow commands are given first, followed by
less common or more advanced commands.

Main commands:
  init          Prepare your working directory for other commands
  validate      Check whether the configuration is valid
  plan          Show changes required by the current configuration
  apply         Create or update infrastructure
  destroy       Destroy previously-created infrastructure

All other commands:
  console       Try OpenTF expressions at an interactive command prompt
  fmt           Reformat your configuration in the standard style
  force-unlock  Release a stuck lock on the current workspace
  get           Install or upgrade remote OpenTF modules
  graph         Generate a Graphviz graph of the steps in an operation
  ...
```
