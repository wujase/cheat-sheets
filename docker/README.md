# Overview

- [docker](https://www.docker.com/)
- [Understanding Docker Hub Rate Limiting](https://www.docker.com/increase-rate-limits)

# Cheat Sheets

| Command                                                                                           | Description                              | Note                                                                                  |
|---------------------------------------------------------------------------------------------------|------------------------------------------|---------------------------------------------------------------------------------------|
| `docker help`                                                                                     |                                          |                                                                                       |
| `docker --help`                                                                                   |                                          |                                                                                       |
| `docker [command] --help`                                                                         |                                          |                                                                                       |
| &nbsp;                                                                                            |                                          |                                                                                       |
| `docker container ls [options]`                                                                   | Display all docker containers.           | [options](https://docs.docker.com/engine/reference/commandline/container_ls/#options) |
| `docker exec [options] [container] [command]`                                                     | Execute a command in a docker container. | [options](https://docs.docker.com/engine/reference/commandline/exec/#options)         |
| `docker image build [options] [path or url]`                                                      | Build a docker image.                    | [options](https://docs.docker.com/engine/reference/commandline/image_build/#options)  |
| `docker image ls [options]`                                                                       | Display all docker images.               | [options](https://docs.docker.com/engine/reference/commandline/image_ls/#options)     |
| `docker image pull [options] [image-name]:[image-tag]`                                            | Pull a docker image.                     | [options](https://docs.docker.com/engine/reference/commandline/image_pull/#options)   |
| `docker image push [options] [image-name]:[image-tag]`                                            | Push a docker image.                     | [options](https://docs.docker.com/engine/reference/commandline/image_push/#options)   |
| `docker image tag [source-image-name]:[source-image-tag] [target-image-name]:[target-image-name]` | Tag a docker image.                      |                                                                                       |
| `docker login [options] [registry]`                                                               | Log in to a docker registry.             | [options](https://docs.docker.com/engine/reference/commandline/login/#options)        |
| `docker logout [registry]`                                                                        | Log out from a docker registry.          |                                                                                       |
| `docker logs [options] [container]`                                                               | Display all logs of a docker container.  | [options](https://docs.docker.com/engine/reference/commandline/logs/#options)         |
| `docker version [options]`                                                                        | Display the docker version.              | [options](https://docs.docker.com/engine/reference/commandline/version/#options)      |
