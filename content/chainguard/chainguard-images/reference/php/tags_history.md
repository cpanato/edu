---
title: "php Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the php Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-07-03 00:33:11
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/php/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/php/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/php/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/php/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)                                | Last Changed | Digest                                                                    |
|----------------------------------------|--------------|---------------------------------------------------------------------------|
|  `latest`                              | June 28th    | `sha256:9097f611385f2f6886f3518ba17cc598880335402aaf4de6aa373194f1b5ff70` |
|  `latest-dev`                          | June 28th    | `sha256:83707f647d1378d1cbb5f44f5ea42f15a9cc3bd7802f684492e4a9246d9a97b1` |
|  `latest-dev-fpm-dev` `latest-fpm-dev` | June 28th    | `sha256:d753f88d3226ebd74d4004229f83b65a23c5fc6d6ce6f9e0d38d4122d8635ced` |
|  `latest-dev-fpm` `latest-fpm`         | June 28th    | `sha256:4939097caa3e3bceb729da22ddbbd3b741c3125f8a8a513349b6aad3f72dea73` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                                                        | Last Changed | Digest                                                                    |
|--------------------------------------------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `8.3.9` `latest` `8.3` `8`                                                    | July 2nd     | `sha256:5837a3b0835de89e14263c88645d4fa4c249751e29f07af14ea84d760ba29ac8` |
|  `8.3.9-fpm-dev` `latest-fpm-dev` `8.3.9-r0-fpm-dev` `8-fpm-dev` `8.3-fpm-dev` | July 2nd     | `sha256:10957467d72900f234d18f02e07627940c0a93490cf019865250850525fb4877` |
|  `8-dev` `latest-dev` `8.3.9-dev` `8.3-dev`                                    | July 2nd     | `sha256:c835b57ad14bee767752ebf13968aa7fd690ad2010bd73b4f3e8fa2662b9464e` |
|  `8.2.21-r0-fpm-dev` `8.2.21-fpm-dev` `8.2-fpm-dev`                            | July 2nd     | `sha256:e9372b7474cda0dda827ff8caeb4bddbc766f87ad9587190b9c34ea125153f00` |
|  `8-fpm` `8.3.9-r0-fpm` `latest-fpm` `8.3-fpm` `8.3.9-fpm`                     | July 2nd     | `sha256:8a6d7c3128f1c2c3c74fd328bb8e2a761eb7021ef35de9728d5ebe17df569052` |
|  `8.2` `8.2.21`                                                                | July 2nd     | `sha256:3cae812df772091752ccc8e8b5940726998a59d05e474e5396c200a4a6ffbca9` |
|  `8.2.21-r0-fpm` `8.2-fpm` `8.2.21-fpm`                                        | July 2nd     | `sha256:d5180708e06d63f7c597149f608f629836a632e5052f8cb1a49da48c6899899c` |
|  `8.2-dev` `8.2.21-dev`                                                        | July 2nd     | `sha256:6dbe9f93aaecab99288f8c360e486afc227e455c9287ad88693550b14751840b` |
|  `8.3.8-r4-fpm` `8.3.8-fpm`                                                    | June 28th    | `sha256:249b462f275684051f7bab1462ddfe492108b5d8632384ff00cac91472d19222` |
|  `8.2.20`                                                                      | June 28th    | `sha256:278b56701381cc44247ad96ccc63c1ce00b428df12e3e31248e0929e7ab9dc5c` |
|  `8.2.20-dev`                                                                  | June 28th    | `sha256:300136c2fb18fc2e6310a31020d4dfbf4e3cbed22ad65f57aa583fbdb8c0fca0` |
|  `8.3.8-r4-fpm-dev` `8.3.8-fpm-dev`                                            | June 28th    | `sha256:dba8716b2d9403ec611f98b9673e64771a48fbc0a0fe45205c2dcc54b7a579b6` |
|  `8.2.20-r4-fpm-dev` `8.2.20-fpm-dev`                                          | June 28th    | `sha256:3759834054efdfa516d6242ef24bc88eaccd9adc1f03a6e08397b3399eb21633` |
|  `8.3.8-dev`                                                                   | June 28th    | `sha256:3f43d4be994c677840606013323e5cb8f889840e5123eeb69f58b93ee9ea4051` |
|  `8.2.20-fpm` `8.2.20-r4-fpm`                                                  | June 28th    | `sha256:e47d683f944620bbc167fd7ff77f104f5f7347f07eb2f5492ab34541f34003a7` |
|  `8.3.8`                                                                       | June 28th    | `sha256:1bc05bb186265b0a10d9a8fd0463ba6e4ec355440cc2c79b94ab4009c7e25cd7` |

