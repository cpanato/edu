---
title: "harbor-portal Image Details"
type: "article"
unlisted: true
description: "Detailed information about the public harbor-portal Chainguard Image."
date: 2023-03-07T11:07:52+02:00
lastmod: 2024-06-23 00:43:06
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 550
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/harbor-portal/" >}}
{{< tab title="Details" active=true url="/chainguard/chainguard-images/reference/harbor-portal/image_specs/" >}}
{{< tab title="Tags History" active=false url="/chainguard/chainguard-images/reference/harbor-portal/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/harbor-portal/provenance_info/" >}}
{{</ tabs >}}

This page shows detailed information about the Chainguard **harbor-portal** Image.

|              | latest-dev               | latest                   |
|--------------|--------------------------|--------------------------|
| Default User | `nginx`                  | `nginx`                  |
| Entrypoint   | `nginx -g 'daemon off;'` | `nginx -g 'daemon off;'` |
| CMD          | not specified            | not specified            |
| Workdir      | `/`                      | `/`                      |
| Has apk?     | yes                      | no                       |
| Has a shell? | yes                      | no                       |

Check the [tags history page](/chainguard/chainguard-images/reference/harbor-portal/tags_history/) for the full list of available tags.

## Packages Included
The table shows package distribution across variants.

|                                   | latest-dev | latest |
|-----------------------------------|------------|--------|
| `apk-tools`                       | X          |        |
| `bash`                            | X          |        |
| `busybox`                         | X          |        |
| `ca-certificates-bundle`          | X          | X      |
| `chainguard-baselayout`           | X          | X      |
| `git`                             | X          |        |
| `glibc`                           | X          | X      |
| `glibc-locale-posix`              | X          | X      |
| `harbor-2.11-portal`              | X          | X      |
| `harbor-2.11-portal-nginx-config` | X          | X      |
| `ld-linux`                        | X          | X      |
| `libbrotlicommon1`                | X          |        |
| `libbrotlidec1`                   | X          |        |
| `libcrypt1`                       | X          | X      |
| `libcrypto3`                      | X          | X      |
| `libcurl-openssl4`                | X          |        |
| `libexpat1`                       | X          |        |
| `libgcc`                          | X          | X      |
| `libidn2`                         | X          |        |
| `libnghttp2-14`                   | X          |        |
| `libpcre2-8-0`                    | X          |        |
| `libpsl`                          | X          |        |
| `libssl3`                         | X          | X      |
| `libstdc++`                       | X          | X      |
| `libunistring`                    | X          |        |
| `libxcrypt`                       | X          | X      |
| `ncurses`                         | X          |        |
| `ncurses-terminfo-base`           | X          |        |
| `nginx-mainline`                  | X          | X      |
| `pcre`                            | X          | X      |
| `wget`                            | X          |        |
| `wolfi-baselayout`                | X          | X      |
| `zlib`                            | X          | X      |

