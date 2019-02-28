# [Paste](https://hub.docker.com/r/p3lim/paste/)

[Paste](https://github.com/p3lim/paste) server for all your code sharing needs.

### Build Info

- Image: [p3lim/alpine:3.8](https://github.com/p3lim/docker-alpine)
- Ports: _5000_
- Volumes:
	- `/config`
- Environment:
	- `PUID` (user id)
	- `PGID` (user group)
	- `TZ` (timezone, e.g. `Europe/Paris`)
	- `PATH_LENGTH` (defaults to `4`)
