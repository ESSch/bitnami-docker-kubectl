
# What is Kubectl?

> Kubectl is the Kubernetes command line interface.

[Overview of kubectl](https://kubernetes.io/docs/reference/kubectl/overview/)

# TL;DR;

```bash
$ docker run --name kubectl bitnami/kubectl:latest
```

# Why use Bitnami Images?

* Bitnami closely tracks upstream source changes and promptly publishes new versions of this image using our automated systems.
* With Bitnami images the latest bug fixes and features are available as soon as possible.
* Bitnami containers, virtual machines and cloud images use the same components and configuration approach - making it easy to switch between formats based on your project needs.
* All our images are based on [minideb](https://github.com/bitnami/minideb) a minimalist Debian based container image which gives you a small base container image and the familiarity of a leading linux distribution.
* All Bitnami images available in Docker Hub are signed with [Docker Content Trust (DTC)](https://docs.docker.com/engine/security/trust/content_trust/). You can use `DOCKER_CONTENT_TRUST=1` to verify the integrity of the images.
* Bitnami container images are released daily with the latest distribution packages available.


> This [CVE scan report](https://quay.io/repository/bitnami/kubectl?tab=tags) contains a security report with all open CVEs. To get the list of actionable security issues, find the "latest" tag, click the vulnerability report link under the corresponding "Security scan" field and then select the "Only show fixable" filter on the next page.

# Supported tags and respective `Dockerfile` links

Learn more about the Bitnami tagging policy and the difference between rolling tags and immutable tags [in our documentation page](https://docs.bitnami.com/containers/how-to/understand-rolling-tags-containers/).


* [`1.16-ol-7`, `1.16.0-ol-7-r0` (1.16/ol-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.16.0-ol-7-r0/1.16/ol-7/Dockerfile)
* [`1.16-debian-9`, `1.16.0-debian-9-r1`, `1.16`, `1.16.0`, `1.16.0-r1` (1.16/debian-9/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.16.0-debian-9-r1/1.16/debian-9/Dockerfile)
* [`1.14-ol-7`, `1.14.3-ol-7-r115` (1.14/ol-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.14.3-ol-7-r115/1.14/ol-7/Dockerfile)
* [`1.14-debian-9`, `1.14.3-debian-9-r108`, `1.14`, `1.14.3`, `1.14.3-r108` (1.14/debian-9/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.14.3-debian-9-r108/1.14/debian-9/Dockerfile)
* [`1.13-ol-7`, `1.13.4-ol-7-r206` (1.13/ol-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.13.4-ol-7-r206/1.13/ol-7/Dockerfile)
* [`1.13-debian-9`, `1.13.4-debian-9-r191`, `1.13`, `1.13.4`, `1.13.4-r191` (1.13/debian-9/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.13.4-debian-9-r191/1.13/debian-9/Dockerfile)

Subscribe to project updates by watching the [bitnami/kubectl GitHub repo](https://github.com/bitnami/bitnami-docker-kubectl).

# Get this image

The recommended way to get the Bitnami Kubectl Docker Image is to pull the prebuilt image from the [Docker Hub Registry](https://hub.docker.com/r/bitnami/kubectl).

```bash
$ docker pull bitnami/kubectl:latest
```

To use a specific version, you can pull a versioned tag. You can view the [list of available versions](https://hub.docker.com/r/bitnami/kubectl/tags/) in the Docker Hub Registry.

```bash
$ docker pull bitnami/kubectl:[TAG]
```

If you wish, you can also build the image yourself.

```bash

```

# Configuration

## Running commands

To run commands inside this container you can use `docker run`, for example to execute `kubectl --version` you can follow the example below:

```bash
$ docker run --rm --name kubectl bitnami/kubectl:latest -- --version
```

Consult the [Kubectl Reference Documentation](https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands) to find the completed list of commands available.

# Contributing

We'd love for you to contribute to this container. You can request new features by creating an [issue](https://github.com/bitnami/bitnami-docker-kubectl/issues), or submit a [pull request](https://github.com/bitnami/bitnami-docker-kubectl/pulls) with your contribution.

# Issues

If you encountered a problem running this container, you can file an [issue](https://github.com/bitnami/bitnami-docker-kubectl/issues). For us to provide better support, be sure to include the following information in your issue:

- Host OS and version
- Docker version (`docker version`)
- Output of `docker info`
- Version of this container
- The command you used to run the container, and any relevant output you saw (masking any sensitive information)

# License

Copyright 2019 Bitnami

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
