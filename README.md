# [`dotwee/matrix-sydent`](https://github.com/dotWee/docker-matrix-sydent)

![github status](https://img.shields.io/github/workflow/status/dotwee/docker-matrix-sydent/cron/master?logo=GitHub)
![github activity](https://img.shields.io/github/last-commit/dotwee/docker-matrix-sydent?logo=github)
![github open issues](https://badgen.net/github/open-issues/dotwee/docker-matrix-sydent?icon=github)
![docker pulls](https://badgen.net/docker/pulls/dotwee/matrix-sydent?icon=docker&label=pulls)

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

### available tags

- `linux/arm64`
- `linux/amd64`

## run

see the [official docker sydent docs](https://github.com/matrix-org/sydent#docker).

## references

- official matrix.org [sydent project site](https://matrix.org/docs/projects/other/sydent)
- [matrix-org/sydent](https://github.com/matrix-org/sydent) git repository
- prebuild docker image hosted on [docker hub](https://hub.docker.com/r/dotwee/matrix-sydent) and [github packages](https://github.com/dotWee/docker-matrix-sydent/pkgs/container/matrix-sydent)
