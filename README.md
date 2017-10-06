# Ubuntu LTS with OpenJDK #

This image extends [ubuntu](https://hub.docker.com/r/_/ubuntu/) and serves as a base image. It only includes OpenJDK and *wget*.

## Supported Tags ##

`16.04-jdk8`, `latest` [*(Dockerfile)*](https://github.com/kraitv3/docker-ubuntu-jdk/blob/master/Dockerfile)

## Extending the Image ##

```
FROM kraitv3/ubuntu-jdk:<tag>
...
# Do your stuff
...
```

## Running the Image ##

Instead of extending the image, you can run it in interactive mode to test some statements on the command line:

```
docker run -it kraitv3/ubuntu-jdk:<tag>
```

