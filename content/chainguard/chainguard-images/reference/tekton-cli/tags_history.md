---
title: "tekton-cli Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the tekton-cli Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-06-26 00:35:03
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/tekton-cli/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/tekton-cli/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/tekton-cli/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/tekton-cli/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` | June 24th    | `sha256:e1cdeef1dd4f09b53b83a7c09d72107e8e233198e59cdab50e16d4bd41c7f729` |
|  `latest`     | June 19th    | `sha256:8def59fe55ddff4135c94daf0fe122f7378366ef49cae8646354e28c1570062a` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                       | Last Changed | Digest                                                                    |
|-----------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `0.37-dev` `0-dev` `0.37.0-dev` `latest-dev` | June 25th    | `sha256:e14203e89263a54cfb2d0701f39420727c72336994f1c4033149811f22880fd3` |
|  `0.37.0` `0.37` `0` `latest`                 | June 25th    | `sha256:4bf7501ca4fd64d49c33b27be11cefdec761a52e24b1b42fb2f9343866e9d373` |

