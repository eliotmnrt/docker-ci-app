# Docker CI App

![Docker Pulls](https://img.shields.io/docker/pulls/eliot843/docker-ci-app)
![Docker Image Size](https://img.shields.io/docker/image-size/eliot843/docker-ci-app)

## Quick Start

```bash
docker pull username/docker-ci-app:master
docker run -p 3000:3000 username/docker-ci-app:master
curl http://localhost:3000
```

## Available Tags

- `master` - Most recent master branch
- `main` - Main branch
- `v1.0.0` - Specific versions
- `sha-abc123` - Specific commits

## Registries

- Docker Hub: `docker pull eliot843/docker-ci-app`

## Environment Variables

- `PORT` - Server port (default: 3000)
- `APP_VERSION` - Application version
- `GIT_COMMIT` - Git commit SHA
