<!--

********************************************************************************

WARNING:

    DO NOT EDIT "irssi/README.md"

    IT IS AUTO-GENERATED

    (from the other files in "irssi/" combined with a set of templates)

********************************************************************************

-->

**Note:** this is the "per-architecture" repository for the `windows-amd64` builds of [the `irssi` official image](https://hub.docker.com/_/irssi) -- for more information, see ["Architectures other than amd64?" in the official images documentation](https://github.com/docker-library/official-images#architectures-other-than-amd64) and ["An image's source changed in Git, now what?" in the official images FAQ](https://github.com/docker-library/faq#an-images-source-changed-in-git-now-what).

# Quick reference

-	**Maintained by**:  
	[Jessie and Tianon (of the Docker Community)](https://github.com/jessfraz/irssi), [with the appreciation of the Irssi Project](https://twitter.com/GeertHauwaerts/status/559131523145035776)

-	**Where to get help**:  
	[the Docker Community Forums](https://forums.docker.com/), [the Docker Community Slack](https://dockr.ly/slack), or [Stack Overflow](https://stackoverflow.com/search?tab=newest&q=docker)

# Supported tags and respective `Dockerfile` links

**WARNING:** THIS IMAGE *IS NOT SUPPORTED* ON THE `windows-amd64` ARCHITECTURE

[![winamd64/irssi build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/windows-amd64/job/irssi.svg?label=winamd64/irssi%20%20build%20job)](https://doi-janky.infosiftr.net/job/multiarch/job/windows-amd64/job/irssi/)

# Quick reference (cont.)

-	**Where to file issues**:  
	[https://github.com/jessfraz/irssi/issues](https://github.com/jessfraz/irssi/issues)

-	**Supported architectures**: ([more info](https://github.com/docker-library/official-images#architectures-other-than-amd64))  
	[`amd64`](https://hub.docker.com/r/amd64/irssi/), [`arm32v5`](https://hub.docker.com/r/arm32v5/irssi/), [`arm32v6`](https://hub.docker.com/r/arm32v6/irssi/), [`arm32v7`](https://hub.docker.com/r/arm32v7/irssi/), [`arm64v8`](https://hub.docker.com/r/arm64v8/irssi/), [`i386`](https://hub.docker.com/r/i386/irssi/), [`mips64le`](https://hub.docker.com/r/mips64le/irssi/), [`ppc64le`](https://hub.docker.com/r/ppc64le/irssi/), [`s390x`](https://hub.docker.com/r/s390x/irssi/)

-	**Published image artifact details**:  
	[repo-info repo's `repos/irssi/` directory](https://github.com/docker-library/repo-info/blob/master/repos/irssi) ([history](https://github.com/docker-library/repo-info/commits/master/repos/irssi))  
	(image metadata, transfer size, etc)

-	**Image updates**:  
	[official-images repo's `library/irssi` label](https://github.com/docker-library/official-images/issues?q=label%3Alibrary%2Firssi)  
	[official-images repo's `library/irssi` file](https://github.com/docker-library/official-images/blob/master/library/irssi) ([history](https://github.com/docker-library/official-images/commits/master/library/irssi))

-	**Source of this description**:  
	[docs repo's `irssi/` directory](https://github.com/docker-library/docs/tree/master/irssi) ([history](https://github.com/docker-library/docs/commits/master/irssi))

# What is irssi?

Irssi is a terminal based IRC client for UNIX systems. It also supports SILC and ICB protocols via plugins. Some people refer to it as 'the client of the future'.

> [irssi.org](http://irssi.org)

![logo](https://raw.githubusercontent.com/docker-library/docs/633afc6f794a31463888319d9f0c3cc0801d81e3/irssi/logo.png)

# How to use this image

Because it is unlikely any two irssi users have the same configuration preferences, this image does not include an irssi configuration. To configure irssi to your liking, please refer to [upstream's excellent (and comprehensive) +documentation](http://irssi.org/documentation).

Be sure to also checkout the [awesome scripts](https://github.com/irssi/scripts.irssi.org) you can download to customize your irssi configuration.

## Directly via bind mount

On a Linux system, build and launch a container named `my-running-irssi` like this:

```console
$ docker run -it --name my-running-irssi -e TERM -u $(id -u):$(id -g) \
    --log-driver=none \
    -v $HOME/.irssi:/home/user/.irssi:ro \
    -v /etc/localtime:/etc/localtime:ro \
    winamd64/irssi
```

We specify `--log-driver=none` to avoid storing useless interactive terminal data.

On a Mac OS X system, run the same image using:

```console
$ docker run -it --name my-running-irssi -e TERM -u $(id -u):$(id -g) \
    --log-driver=none \
    -v $HOME/.irssi:/home/user/.irssi:ro \
    winamd64/irssi
```

You omit `/etc/localtime` on Mac OS X because `boot2docker` doesn't use this file.

# License

View [license information](https://github.com/irssi/irssi/blob/master/COPYING) for the software contained in this image.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

Some additional license information which was able to be auto-detected might be found in [the `repo-info` repository's `irssi/` directory](https://github.com/docker-library/repo-info/tree/master/repos/irssi).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
