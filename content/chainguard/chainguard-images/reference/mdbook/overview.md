---
title: "Image Overview: mdbook"
type: "article"
description: "Overview: mdbook Chainguard Image"
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

[cgr.dev/chainguard/mdbook](https://github.com/chainguard-images/images/tree/main/images/mdbook)

| Tag (s)   | Last Changed | Digest                                                                    |
|-----------|--------------|---------------------------------------------------------------------------|
|  `latest` | July 18th    | `sha256:91040a61249724af59e45349e98fd6460c8d3deaea7107451cb097dd920bb2c1` |



This is an image that contains mdbook.

## Get It!

The image is available on `cgr.dev`:

```
docker pull cgr.dev/chainguard/mdbook:latest
```

# Usage

Example: build an mdbook project in the `/work` directory

```
docker run --rm \
    -v "${PWD}":/work \
    -w /work \
    cgr.dev/chainguard/mdbook:latest
    init --force --title chainguard-images --ignore git
```
