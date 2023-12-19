---
title: "kubeflow-centraldashboard Image Variants"
type: "article"
unlisted: true
description: "Detailed information about the public kubeflow-centraldashboard Chainguard Image variants"
date: 2023-12-08 00:32:20
lastmod: 2023-12-08 00:32:20
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 550
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/kubeflow-centraldashboard/" >}}
{{< tab title="Variants" active=true url="/chainguard/chainguard-images/reference/kubeflow-centraldashboard/image_specs/" >}}
{{< tab title="Tags History" active=false url="/chainguard/chainguard-images/reference/kubeflow-centraldashboard/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/kubeflow-centraldashboard/provenance_info/" >}}
{{</ tabs >}}

This page shows detailed information about all public variants of the Chainguard **kubeflow-centraldashboard** Image.

## Variants Compared
The **kubeflow-centraldashboard** Chainguard Image currently has 2 public variants: 

- `latest-dev`
- `latest`

The table has detailed information about each of these variants.

|              | latest-dev           | latest               |
|--------------|----------------------|----------------------|
| Default User | `nonroot`            | `nonroot`            |
| Entrypoint   | `/usr/bin/npm start` | `/usr/bin/npm start` |
| CMD          | not specified        | not specified        |
| Workdir      | `/app`               | `/app`               |
| Has apk?     | yes                  | no                   |
| Has a shell? | yes                  | yes                  |

Check the [tags history page](/chainguard/chainguard-images/reference/kubeflow-centraldashboard/tags_history/) for the full list of available tags.

## Packages Included
The table shows package distribution across variants.

|                             | latest-dev | latest |
|-----------------------------|------------|--------|
| `apk-tools`                 | X          |        |
| `bash`                      | X          |        |
| `busybox`                   | X          | X      |
| `c-ares`                    | X          | X      |
| `ca-certificates-bundle`    | X          | X      |
| `git`                       | X          |        |
| `glibc`                     | X          | X      |
| `glibc-locale-posix`        | X          | X      |
| `icu`                       | X          | X      |
| `kubeflow-centraldashboard` | X          | X      |
| `ld-linux`                  | X          | X      |
| `libbrotlicommon1`          | X          | X      |
| `libbrotlidec1`             | X          | X      |
| `libbrotlienc1`             | X          | X      |
| `libcrypt1`                 | X          | X      |
| `libcrypto3`                | X          | X      |
| `libcurl-openssl4`          | X          |        |
| `libexpat1`                 | X          |        |
| `libgcc`                    | X          | X      |
| `libnghttp2-14`             | X          | X      |
| `libpcre2-8-0`              | X          |        |
| `libssl3`                   | X          | X      |
| `libstdc++`                 | X          | X      |
| `ncurses`                   | X          |        |
| `ncurses-terminfo-base`     | X          |        |
| `nodejs-18`                 | X          | X      |
| `npm`                       | X          | X      |
| `openssl-config`            | X          | X      |
| `wolfi-baselayout`          | X          | X      |
| `zlib`                      | X          | X      |
