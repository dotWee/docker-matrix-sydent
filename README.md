# [docker-matrix-sydent](https://github.com/dotWee/docker-matrix-sydent)

<a href="https://github.com/dotWee/docker-matrix-sydent/actions/workflows/cron.yml"><img src="https://github.com/dotWee/docker-matrix-sydent/actions/workflows/cron.yml/badge.svg"/></a>
<a href="https://github.com/dotWee/docker-matrix-sydent/actions"><img src="https://badgen.net/github/checks/dotwee/docker-matrix-sydent?icon=github&label=status"/></a>
<a href="https://github.com/dotwee/docker-matrix-sydent/blob/master/LICENSE"><img src="https://badgen.net/github/license/dotwee/docker-matrix-sydent?color=cyan&icon=github"/></a>
<a href="https://github.com/dotwee/docker-matrix-sydent/pulls"><img alt="GitHub pullrequests" src="https://badgen.net/github/prs/dotwee/docker-matrix-sydent?label=pull-requests&icon=github"/></a>
<a href="https://github.com/dotwee/docker-matrix-sydent/issues"><img src="https://badgen.net/github/issues/dotwee/docker-matrix-sydent?icon=github"/></a>
<a href="https://cloud.docker.com/u/dotwee/repository/docker/dotwee/matrix-sydent"><img src="https://badgen.net/docker/size/dotwee/matrix-sydent?icon=docker&label=size"/></a>
<a href="https://cloud.docker.com/u/dotwee/repository/docker/dotwee/matrix-sydent"><img src="https://badgen.net/docker/pulls/dotwee/matrix-sydent?icon=docker&label=pulls"/></a>

this repo is on charge of checking everyday if there is a new [Sydent](https://github.com/matrix-org/sydent/) version and create the proper docker image and push it to the [docker hub](https://hub.docker.com/r/dotwee/matrix-sydent) and [github packages](https://github.com/users/dotWee/packages/container/package/matrix-sydent) as need it.

<small>currently supported & tested arch builds are `linux/amd64` & `linux/arm64`.</small>

## pull

### from [docker hub](https://hub.docker.com/r/dotwee/matrix-sydent)

```bash
$ docker pull dotwee/matrix-sydent:latest
```

### from [github packages](https://github.com/dotWee/docker-matrix-sydent/pkgs/container/matrix-sydent)

```bash
$ docker pull ghcr.io/dotwee/matrix-sydent:latest
```

## run

see the [official docker sydent docs](https://github.com/matrix-org/sydent#docker).

## references

- official matrix.org [sydent project site](https://matrix.org/docs/projects/other/sydent)
- [matrix-org/sydent](https://github.com/matrix-org/sydent) git repository
- prebuild docker image hosted on [docker hub](https://hub.docker.com/r/dotwee/matrix-sydent) and [github packages](https://github.com/dotWee/docker-matrix-sydent/pkgs/container/matrix-sydent)
