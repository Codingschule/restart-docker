# restart-docker

A database training-environment for the restart-course at [codingschule.de](https://https://www.codingschule.de/en/cloud)

## Installation

### Docker Installation

You need a working docker setup. You can find all you need [here](https://docs.docker.com/engine/install/).

### Git Installation

It's good idea to have git installed on your system. You can find all you need [here](https://github.com/git-guides/install-git)

### Run the Environment

Here are the steps you can follow to download the code and run the docker compose file:

#### clone the repository

Use your terminal to navigate to the directory you want to clone the repository and use the git clone command to clone the repository

```shell
# clone the repository
git clone https://github.com/Codingschule/restart-docker/tree/main
```

Cd into the directory, build and run your environment:

```shell
# build the environment
docker compose build

# run the environment
docker compose up -d
```
