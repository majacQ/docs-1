<!--

********************************************************************************

WARNING:

    DO NOT EDIT "openjdk/README.md"

    IT IS AUTO-GENERATED

    (from the other files in "openjdk/" combined with a set of templates)

********************************************************************************

-->

**Note:** this is the "per-architecture" repository for the `windows-amd64` builds of [the `openjdk` official image](https://hub.docker.com/_/openjdk) -- for more information, see ["Architectures other than amd64?" in the official images documentation](https://github.com/docker-library/official-images#architectures-other-than-amd64) and ["An image's source changed in Git, now what?" in the official images FAQ](https://github.com/docker-library/faq#an-images-source-changed-in-git-now-what).

# Quick reference

-	**Maintained by**:  
	[the Docker Community](https://github.com/docker-library/openjdk)

-	**Where to get help**:  
	[the Docker Community Forums](https://forums.docker.com/), [the Docker Community Slack](https://dockr.ly/slack), or [Stack Overflow](https://stackoverflow.com/search?tab=newest&q=docker)

# Supported tags and respective `Dockerfile` links

(See ["What's the difference between 'Shared' and 'Simple' tags?" in the FAQ](https://github.com/docker-library/faq#whats-the-difference-between-shared-and-simple-tags).)

## Simple Tags

-	[`17-ea-25-jdk-windowsservercore-1809`, `17-ea-25-windowsservercore-1809`, `17-ea-jdk-windowsservercore-1809`, `17-ea-windowsservercore-1809`, `17-jdk-windowsservercore-1809`, `17-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/45e05473d1b545373bd1174083d74e0b53d0aa35/17/jdk/windows/windowsservercore-1809/Dockerfile)
-	[`17-ea-25-jdk-windowsservercore-ltsc2016`, `17-ea-25-windowsservercore-ltsc2016`, `17-ea-jdk-windowsservercore-ltsc2016`, `17-ea-windowsservercore-ltsc2016`, `17-jdk-windowsservercore-ltsc2016`, `17-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/45e05473d1b545373bd1174083d74e0b53d0aa35/17/jdk/windows/windowsservercore-ltsc2016/Dockerfile)
-	[`17-ea-25-jdk-nanoserver-1809`, `17-ea-25-nanoserver-1809`, `17-ea-jdk-nanoserver-1809`, `17-ea-nanoserver-1809`, `17-jdk-nanoserver-1809`, `17-nanoserver-1809`](https://github.com/docker-library/openjdk/blob/45e05473d1b545373bd1174083d74e0b53d0aa35/17/jdk/windows/nanoserver-1809/Dockerfile)
-	[`16.0.1-jdk-windowsservercore-1809`, `16.0.1-windowsservercore-1809`, `16.0-jdk-windowsservercore-1809`, `16.0-windowsservercore-1809`, `16-jdk-windowsservercore-1809`, `16-windowsservercore-1809`, `jdk-windowsservercore-1809`, `windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/277bd48c8482ecbc70225442328ef34a7c8ff139/16/jdk/windows/windowsservercore-1809/Dockerfile)
-	[`16.0.1-jdk-windowsservercore-ltsc2016`, `16.0.1-windowsservercore-ltsc2016`, `16.0-jdk-windowsservercore-ltsc2016`, `16.0-windowsservercore-ltsc2016`, `16-jdk-windowsservercore-ltsc2016`, `16-windowsservercore-ltsc2016`, `jdk-windowsservercore-ltsc2016`, `windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/277bd48c8482ecbc70225442328ef34a7c8ff139/16/jdk/windows/windowsservercore-ltsc2016/Dockerfile)
-	[`16.0.1-jdk-nanoserver-1809`, `16.0.1-nanoserver-1809`, `16.0-jdk-nanoserver-1809`, `16.0-nanoserver-1809`, `16-jdk-nanoserver-1809`, `16-nanoserver-1809`, `jdk-nanoserver-1809`, `nanoserver-1809`](https://github.com/docker-library/openjdk/blob/277bd48c8482ecbc70225442328ef34a7c8ff139/16/jdk/windows/nanoserver-1809/Dockerfile)
-	[`11.0.11-9-jdk-windowsservercore-1809`, `11.0.11-9-windowsservercore-1809`, `11.0.11-jdk-windowsservercore-1809`, `11.0.11-windowsservercore-1809`, `11.0-jdk-windowsservercore-1809`, `11.0-windowsservercore-1809`, `11-jdk-windowsservercore-1809`, `11-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/2bff20bd81e3ce1172d3adefcfb5cb994c8e0e4d/11/jdk/windows/windowsservercore-1809/Dockerfile)
-	[`11.0.11-9-jdk-windowsservercore-ltsc2016`, `11.0.11-9-windowsservercore-ltsc2016`, `11.0.11-jdk-windowsservercore-ltsc2016`, `11.0.11-windowsservercore-ltsc2016`, `11.0-jdk-windowsservercore-ltsc2016`, `11.0-windowsservercore-ltsc2016`, `11-jdk-windowsservercore-ltsc2016`, `11-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/2bff20bd81e3ce1172d3adefcfb5cb994c8e0e4d/11/jdk/windows/windowsservercore-ltsc2016/Dockerfile)
-	[`11.0.11-9-jdk-nanoserver-1809`, `11.0.11-9-nanoserver-1809`, `11.0.11-jdk-nanoserver-1809`, `11.0.11-nanoserver-1809`, `11.0-jdk-nanoserver-1809`, `11.0-nanoserver-1809`, `11-jdk-nanoserver-1809`, `11-nanoserver-1809`](https://github.com/docker-library/openjdk/blob/2bff20bd81e3ce1172d3adefcfb5cb994c8e0e4d/11/jdk/windows/nanoserver-1809/Dockerfile)
-	[`11.0.11-9-jre-windowsservercore-1809`, `11.0.11-jre-windowsservercore-1809`, `11.0-jre-windowsservercore-1809`, `11-jre-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/e1db2c7a51d718978eea6ee608e1dc687627fba4/11/jre/windows/windowsservercore-1809/Dockerfile)
-	[`11.0.11-9-jre-windowsservercore-ltsc2016`, `11.0.11-jre-windowsservercore-ltsc2016`, `11.0-jre-windowsservercore-ltsc2016`, `11-jre-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/e1db2c7a51d718978eea6ee608e1dc687627fba4/11/jre/windows/windowsservercore-ltsc2016/Dockerfile)
-	[`11.0.11-9-jre-nanoserver-1809`, `11.0.11-jre-nanoserver-1809`, `11.0-jre-nanoserver-1809`, `11-jre-nanoserver-1809`](https://github.com/docker-library/openjdk/blob/e1db2c7a51d718978eea6ee608e1dc687627fba4/11/jre/windows/nanoserver-1809/Dockerfile)
-	[`8u292-jdk-windowsservercore-1809`, `8u292-windowsservercore-1809`, `8-jdk-windowsservercore-1809`, `8-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/765a1c4dd6fa4fd9c2a0cf540e9c17ca73eb227b/8/jdk/windows/windowsservercore-1809/Dockerfile)
-	[`8u292-jdk-windowsservercore-ltsc2016`, `8u292-windowsservercore-ltsc2016`, `8-jdk-windowsservercore-ltsc2016`, `8-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/765a1c4dd6fa4fd9c2a0cf540e9c17ca73eb227b/8/jdk/windows/windowsservercore-ltsc2016/Dockerfile)
-	[`8u292-jdk-nanoserver-1809`, `8u292-nanoserver-1809`, `8-jdk-nanoserver-1809`, `8-nanoserver-1809`](https://github.com/docker-library/openjdk/blob/765a1c4dd6fa4fd9c2a0cf540e9c17ca73eb227b/8/jdk/windows/nanoserver-1809/Dockerfile)
-	[`8u292-jre-windowsservercore-1809`, `8-jre-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/765a1c4dd6fa4fd9c2a0cf540e9c17ca73eb227b/8/jre/windows/windowsservercore-1809/Dockerfile)
-	[`8u292-jre-windowsservercore-ltsc2016`, `8-jre-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/765a1c4dd6fa4fd9c2a0cf540e9c17ca73eb227b/8/jre/windows/windowsservercore-ltsc2016/Dockerfile)
-	[`8u292-jre-nanoserver-1809`, `8-jre-nanoserver-1809`](https://github.com/docker-library/openjdk/blob/765a1c4dd6fa4fd9c2a0cf540e9c17ca73eb227b/8/jre/windows/nanoserver-1809/Dockerfile)

## Shared Tags

-	`17-ea-25-jdk`, `17-ea-25`, `17-ea-jdk`, `17-ea`, `17-jdk`, `17`:
	-	[`17-ea-25-jdk-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/45e05473d1b545373bd1174083d74e0b53d0aa35/17/jdk/windows/windowsservercore-1809/Dockerfile)
	-	[`17-ea-25-jdk-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/45e05473d1b545373bd1174083d74e0b53d0aa35/17/jdk/windows/windowsservercore-ltsc2016/Dockerfile)
-	`17-ea-25-jdk-windowsservercore`, `17-ea-25-windowsservercore`, `17-ea-jdk-windowsservercore`, `17-ea-windowsservercore`, `17-jdk-windowsservercore`, `17-windowsservercore`:
	-	[`17-ea-25-jdk-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/45e05473d1b545373bd1174083d74e0b53d0aa35/17/jdk/windows/windowsservercore-1809/Dockerfile)
	-	[`17-ea-25-jdk-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/45e05473d1b545373bd1174083d74e0b53d0aa35/17/jdk/windows/windowsservercore-ltsc2016/Dockerfile)
-	`17-ea-25-jdk-nanoserver`, `17-ea-25-nanoserver`, `17-ea-jdk-nanoserver`, `17-ea-nanoserver`, `17-jdk-nanoserver`, `17-nanoserver`:
	-	[`17-ea-25-jdk-nanoserver-1809`](https://github.com/docker-library/openjdk/blob/45e05473d1b545373bd1174083d74e0b53d0aa35/17/jdk/windows/nanoserver-1809/Dockerfile)
-	`16.0.1-jdk`, `16.0.1`, `16.0-jdk`, `16.0`, `16-jdk`, `16`, `jdk`, `latest`:
	-	[`16.0.1-jdk-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/277bd48c8482ecbc70225442328ef34a7c8ff139/16/jdk/windows/windowsservercore-1809/Dockerfile)
	-	[`16.0.1-jdk-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/277bd48c8482ecbc70225442328ef34a7c8ff139/16/jdk/windows/windowsservercore-ltsc2016/Dockerfile)
-	`16.0.1-jdk-windowsservercore`, `16.0.1-windowsservercore`, `16.0-jdk-windowsservercore`, `16.0-windowsservercore`, `16-jdk-windowsservercore`, `16-windowsservercore`, `jdk-windowsservercore`, `windowsservercore`:
	-	[`16.0.1-jdk-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/277bd48c8482ecbc70225442328ef34a7c8ff139/16/jdk/windows/windowsservercore-1809/Dockerfile)
	-	[`16.0.1-jdk-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/277bd48c8482ecbc70225442328ef34a7c8ff139/16/jdk/windows/windowsservercore-ltsc2016/Dockerfile)
-	`16.0.1-jdk-nanoserver`, `16.0.1-nanoserver`, `16.0-jdk-nanoserver`, `16.0-nanoserver`, `16-jdk-nanoserver`, `16-nanoserver`, `jdk-nanoserver`, `nanoserver`:
	-	[`16.0.1-jdk-nanoserver-1809`](https://github.com/docker-library/openjdk/blob/277bd48c8482ecbc70225442328ef34a7c8ff139/16/jdk/windows/nanoserver-1809/Dockerfile)
-	`11.0.11-9-jdk`, `11.0.11-9`, `11.0.11-jdk`, `11.0.11`, `11.0-jdk`, `11.0`, `11-jdk`, `11`:
	-	[`11.0.11-9-jdk-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/2bff20bd81e3ce1172d3adefcfb5cb994c8e0e4d/11/jdk/windows/windowsservercore-1809/Dockerfile)
	-	[`11.0.11-9-jdk-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/2bff20bd81e3ce1172d3adefcfb5cb994c8e0e4d/11/jdk/windows/windowsservercore-ltsc2016/Dockerfile)
-	`11.0.11-9-jdk-windowsservercore`, `11.0.11-9-windowsservercore`, `11.0.11-jdk-windowsservercore`, `11.0.11-windowsservercore`, `11.0-jdk-windowsservercore`, `11.0-windowsservercore`, `11-jdk-windowsservercore`, `11-windowsservercore`:
	-	[`11.0.11-9-jdk-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/2bff20bd81e3ce1172d3adefcfb5cb994c8e0e4d/11/jdk/windows/windowsservercore-1809/Dockerfile)
	-	[`11.0.11-9-jdk-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/2bff20bd81e3ce1172d3adefcfb5cb994c8e0e4d/11/jdk/windows/windowsservercore-ltsc2016/Dockerfile)
-	`11.0.11-9-jdk-nanoserver`, `11.0.11-9-nanoserver`, `11.0.11-jdk-nanoserver`, `11.0.11-nanoserver`, `11.0-jdk-nanoserver`, `11.0-nanoserver`, `11-jdk-nanoserver`, `11-nanoserver`:
	-	[`11.0.11-9-jdk-nanoserver-1809`](https://github.com/docker-library/openjdk/blob/2bff20bd81e3ce1172d3adefcfb5cb994c8e0e4d/11/jdk/windows/nanoserver-1809/Dockerfile)
-	`11.0.11-9-jre`, `11.0.11-jre`, `11.0-jre`, `11-jre`:
	-	[`11.0.11-9-jre-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/e1db2c7a51d718978eea6ee608e1dc687627fba4/11/jre/windows/windowsservercore-1809/Dockerfile)
	-	[`11.0.11-9-jre-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/e1db2c7a51d718978eea6ee608e1dc687627fba4/11/jre/windows/windowsservercore-ltsc2016/Dockerfile)
-	`11.0.11-9-jre-windowsservercore`, `11.0.11-jre-windowsservercore`, `11.0-jre-windowsservercore`, `11-jre-windowsservercore`:
	-	[`11.0.11-9-jre-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/e1db2c7a51d718978eea6ee608e1dc687627fba4/11/jre/windows/windowsservercore-1809/Dockerfile)
	-	[`11.0.11-9-jre-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/e1db2c7a51d718978eea6ee608e1dc687627fba4/11/jre/windows/windowsservercore-ltsc2016/Dockerfile)
-	`11.0.11-9-jre-nanoserver`, `11.0.11-jre-nanoserver`, `11.0-jre-nanoserver`, `11-jre-nanoserver`:
	-	[`11.0.11-9-jre-nanoserver-1809`](https://github.com/docker-library/openjdk/blob/e1db2c7a51d718978eea6ee608e1dc687627fba4/11/jre/windows/nanoserver-1809/Dockerfile)
-	`8u292-jdk`, `8u292`, `8-jdk`, `8`:
	-	[`8u292-jdk-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/765a1c4dd6fa4fd9c2a0cf540e9c17ca73eb227b/8/jdk/windows/windowsservercore-1809/Dockerfile)
	-	[`8u292-jdk-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/765a1c4dd6fa4fd9c2a0cf540e9c17ca73eb227b/8/jdk/windows/windowsservercore-ltsc2016/Dockerfile)
-	`8u292-jdk-windowsservercore`, `8u292-windowsservercore`, `8-jdk-windowsservercore`, `8-windowsservercore`:
	-	[`8u292-jdk-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/765a1c4dd6fa4fd9c2a0cf540e9c17ca73eb227b/8/jdk/windows/windowsservercore-1809/Dockerfile)
	-	[`8u292-jdk-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/765a1c4dd6fa4fd9c2a0cf540e9c17ca73eb227b/8/jdk/windows/windowsservercore-ltsc2016/Dockerfile)
-	`8u292-jdk-nanoserver`, `8u292-nanoserver`, `8-jdk-nanoserver`, `8-nanoserver`:
	-	[`8u292-jdk-nanoserver-1809`](https://github.com/docker-library/openjdk/blob/765a1c4dd6fa4fd9c2a0cf540e9c17ca73eb227b/8/jdk/windows/nanoserver-1809/Dockerfile)
-	`8u292-jre`, `8-jre`:
	-	[`8u292-jre-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/765a1c4dd6fa4fd9c2a0cf540e9c17ca73eb227b/8/jre/windows/windowsservercore-1809/Dockerfile)
	-	[`8u292-jre-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/765a1c4dd6fa4fd9c2a0cf540e9c17ca73eb227b/8/jre/windows/windowsservercore-ltsc2016/Dockerfile)
-	`8u292-jre-windowsservercore`, `8-jre-windowsservercore`:
	-	[`8u292-jre-windowsservercore-1809`](https://github.com/docker-library/openjdk/blob/765a1c4dd6fa4fd9c2a0cf540e9c17ca73eb227b/8/jre/windows/windowsservercore-1809/Dockerfile)
	-	[`8u292-jre-windowsservercore-ltsc2016`](https://github.com/docker-library/openjdk/blob/765a1c4dd6fa4fd9c2a0cf540e9c17ca73eb227b/8/jre/windows/windowsservercore-ltsc2016/Dockerfile)
-	`8u292-jre-nanoserver`, `8-jre-nanoserver`:
	-	[`8u292-jre-nanoserver-1809`](https://github.com/docker-library/openjdk/blob/765a1c4dd6fa4fd9c2a0cf540e9c17ca73eb227b/8/jre/windows/nanoserver-1809/Dockerfile)

[![winamd64/openjdk build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/windows-amd64/job/openjdk.svg?label=winamd64/openjdk%20%20build%20job)](https://doi-janky.infosiftr.net/job/multiarch/job/windows-amd64/job/openjdk/)

# Quick reference (cont.)

-	**Where to file issues**:  
	[https://github.com/docker-library/openjdk/issues](https://github.com/docker-library/openjdk/issues)

-	**Supported architectures**: ([more info](https://github.com/docker-library/official-images#architectures-other-than-amd64))  
	[`amd64`](https://hub.docker.com/r/amd64/openjdk/), [`arm64v8`](https://hub.docker.com/r/arm64v8/openjdk/), [`windows-amd64`](https://hub.docker.com/r/winamd64/openjdk/)

-	**Published image artifact details**:  
	[repo-info repo's `repos/openjdk/` directory](https://github.com/docker-library/repo-info/blob/master/repos/openjdk) ([history](https://github.com/docker-library/repo-info/commits/master/repos/openjdk))  
	(image metadata, transfer size, etc)

-	**Image updates**:  
	[official-images repo's `library/openjdk` label](https://github.com/docker-library/official-images/issues?q=label%3Alibrary%2Fopenjdk)  
	[official-images repo's `library/openjdk` file](https://github.com/docker-library/official-images/blob/master/library/openjdk) ([history](https://github.com/docker-library/official-images/commits/master/library/openjdk))

-	**Source of this description**:  
	[docs repo's `openjdk/` directory](https://github.com/docker-library/docs/tree/master/openjdk) ([history](https://github.com/docker-library/docs/commits/master/openjdk))

# What is OpenJDK?

OpenJDK (Open Java Development Kit) is a free and open source implementation of the Java Platform, Standard Edition (Java SE). OpenJDK is the official reference implementation of Java SE since version 7.

> [wikipedia.org/wiki/OpenJDK](http://en.wikipedia.org/wiki/OpenJDK)

Java is a registered trademark of Oracle and/or its affiliates.

![logo](https://raw.githubusercontent.com/docker-library/docs/a3439b66b7980d1811f6b3835a3c541747172970/openjdk/logo.png)

# How to use this image

## Start a Java instance in your app

The most straightforward way to use this image is to use a Java container as both the build and runtime environment. In your `Dockerfile`, writing something along the lines of the following will compile and run your project:

```dockerfile
FROM winamd64/openjdk:7
COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
RUN javac Main.java
CMD ["java", "Main"]
```

You can then run and build the Docker image:

```console
$ docker build -t my-java-app .
$ docker run -it --rm --name my-running-app my-java-app
```

## Compile your app inside the Docker container

There may be occasions where it is not appropriate to run your app inside a container. To compile, but not run your app inside the Docker instance, you can write something like:

```console
$ docker run --rm -v "$PWD":/usr/src/myapp -w /usr/src/myapp winamd64/openjdk:7 javac Main.java
```

This will add your current directory as a volume to the container, set the working directory to the volume, and run the command `javac Main.java` which will tell Java to compile the code in `Main.java` and output the Java class file to `Main.class`.

## Make JVM respect CPU and RAM limits

On startup the JVM tries to detect the number of available CPU cores and RAM to adjust its internal parameters (like the number of garbage collector threads to spawn) accordingly. When the container is ran with limited CPU/RAM then the standard system API used by the JVM for probing it will return host-wide values. This can cause excessive CPU usage and memory allocation errors with older versions of the JVM.

Inside Linux containers, OpenJDK versions 8 and later can correctly detect the container-limited number of CPU cores and available RAM. For all currently supported OpenJDK versions this is turned on by default.

Inside Windows Server (non-Hyper-V) containers, the limit for the number of available CPU cores doesn't work (it's ignored by Host Compute Service). To set the limit manually the JVM can be started as:

```console
$ start /b /wait /affinity 0x3 path/to/java.exe ...
```

In this example CPU affinity hex mask `0x3` will limit the JVM to 2 CPU cores.

RAM limit is supported by Windows Server containers, but currently the JVM cannot detect it. To prevent excessive memory allocations, `-XX:MaxRAM=...` option must be specified with the value that is not bigger than the containers RAM limit.

## Environment variables with periods in their names

Some shells (notably, [the BusyBox `/bin/sh` included in Alpine Linux](https://github.com/docker-library/openjdk/issues/135)) do not support environment variables with periods in the names (which are technically not POSIX compliant), and thus *strip* them instead of passing them through (as Bash does). If your application requires environment variables of this form, either use `CMD ["java", ...]` directly (no shell), or (install and) use Bash explicitly instead of `/bin/sh`.

# Image Variants

The `winamd64/openjdk` images come in many flavors, each designed for a specific use case.

## `winamd64/openjdk:<version>`

This is the defacto image. If you are unsure about what your needs are, you probably want to use this one. It is designed to be used both as a throw away container (mount your source code and start the container to start your app), as well as the base to build other images off of.

## `winamd64/openjdk:<version>-windowsservercore`

This image is based on [Windows Server Core (`microsoft/windowsservercore`)](https://hub.docker.com/r/microsoft/windowsservercore/). As such, it only works in places which that image does, such as Windows 10 Professional/Enterprise (Anniversary Edition) or Windows Server 2016.

For information about how to get Docker running on Windows, please see the relevant "Quick Start" guide provided by Microsoft:

-	[Windows Server Quick Start](https://msdn.microsoft.com/en-us/virtualization/windowscontainers/quick_start/quick_start_windows_server)
-	[Windows 10 Quick Start](https://msdn.microsoft.com/en-us/virtualization/windowscontainers/quick_start/quick_start_windows_10)

# License

View [license information](http://openjdk.java.net/legal/gplv2+ce.html) for the software contained in this image.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

Some additional license information which was able to be auto-detected might be found in [the `repo-info` repository's `openjdk/` directory](https://github.com/docker-library/repo-info/tree/master/repos/openjdk).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
