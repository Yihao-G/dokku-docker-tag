# dokku-docker-tag-command

A simple [Dokku](https://github.com/dokku/dokku) plugin that exposes [`docker tag`](https://docs.docker.com/engine/reference/commandline/tag/) command.

## Installation
```
dokku plugin:install https://github.com/Yihao-G/dokku-docker-tag.git
```

## Usage
```
dokku docker tag SOURCE_IMAGE[:TAG] TARGET_IMAGE[:TAG]
```

To learn more about the available options, see [`docker tag`](https://docs.docker.com/engine/reference/commandline/tag/) command.

## License
MIT
