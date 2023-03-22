# Docker Cobol

[![github/actions/workflow/status](https://img.shields.io/github/actions/workflow/status/brtmvdl/docker-cobol/docker-push.yml)](https://img.shields.io/github/actions/workflow/status/brtmvdl/docker-cobol/docker-push.yml) [![github/license](https://img.shields.io/github/license/brtmvdl/docker-cobol)](https://img.shields.io/github/license/brtmvdl/docker-cobol) [![github/stars](https://img.shields.io/github/stars/brtmvdl/docker-cobol?style=social)](https://img.shields.io/github/stars/brtmvdl/antify?style=social)

Para compilaçao e entrega de projetos escritos em Go Lang

Veja mais em [hub.docker.com/r/tmvdl/cobol](https://hub.docker.com/r/tmvdl/cobol)

## How to use

Install the [Docker](https://docs.docker.com/engine/install/).

### Development

```yaml
version: '3'

services:
  app:
    image: tmvdl/cobol
    volumes:
      - .:/app
```

Run the application

```bash
docker-compose up --build
```

### Production

Run a container

```sh
docker run tmvdl/cobol
```

## License

[MIT](./LICENSE) 
