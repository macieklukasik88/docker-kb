---
tags: docker wsl2
---

- [How to get started with Docker on WSL 2?](#how-to-get-started-with-docker-on-wsl-2)
  - [How to install docker on WSL 2?](#how-to-install-docker-on-wsl-2)
  - [How to configure Docker to start on boot?](#how-to-configure-docker-to-start-on-boot)
  - [How to enable remote access to docker engine (API)?](#how-to-enable-remote-access-to-docker-engine-api)
  - [How to enable command-line completion with oh-my-zsh shell](#how-to-enable-command-line-completion-with-oh-my-zsh-shell)

# How to get started with Docker on WSL 2?

## How to install docker on WSL 2?

1. Follow [this](https://docs.docker.com/engine/install/ubuntu/) guide

## How to configure Docker to start on boot?

1. Follow [this](https://docs.docker.com/engine/install/linux-postinstall/#configure-docker-to-start-on-boot) guide
   1. for me it does not worked out

2. Follow [this](https://docs.microsoft.com/en-us/windows/wsl/wsl-config) guide
   1. wsl.conf file update needed:

 
``` bash
# Set a command to run when a new WSL instance launches. This example starts the Docker container service.
[boot]
command = service docker start
```
## How to enable remote access to docker engine (API)?

1. Follow [this](https://docs.docker.com/engine/install/linux-postinstall/#configure-where-the-docker-daemon-listens-for-connections)

## How to enable command-line completion with oh-my-zsh shell

1. Follow [this](https://docs.docker.com/compose/completion/#zsh) guide

