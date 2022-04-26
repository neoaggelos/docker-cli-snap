# Docker CLI snap

This snap installs the Docker CE CLI.

## Installation

```bash
sudo snap install docker-cli
sudo snap alias docker-cli.docker docker
```

## Usage

Connect to a remote host with SSH:

```bash
export DOCKER_HOST=ssh://ubuntu@myhost
docker ps -a
```
