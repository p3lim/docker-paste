# [Paste](https://hub.docker.com/r/p3lim/paste/)

[Paste](https://github.com/p3lim/paste) server for all your code sharing needs.

### Build Info

- Image: [p3lim/alpine:3.7](https://github.com/p3lim/docker-alpine)
- Ports: _8080_
- Volumes:
	- `/config`
- Environment:
	- `PUID` (user id)
	- `PGID` (user group)
	- `TZ` (timezone, e.g. `Europe/Paris`)
	- `LISTEN_ADDRESS` (defaults to `0.0.0.0`)
	- `LISTEN_PORT` (defaults to `8080`)
	- `PATH_LENGTH` (defaults to `4`)
