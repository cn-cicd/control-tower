# Control Tower Docker Image

[![](https://img.shields.io/docker/pulls/jnonino/control-tower.svg)](https://hub.docker.com/r/jnonino/control-tower/)
[![](hhttps://img.shields.io/docker/build/jnonino/control-tower)](https://hub.docker.com/r/jnonino/control-tower/)
[![](https://img.shields.io/docker/automated/jnonino/control-tower)](https://hub.docker.com/r/jnonino/control-tower/)
[![](https://img.shields.io/docker/stars/jnonino/control-tower)](https://hub.docker.com/r/jnonino/control-tower/)
[![](https://img.shields.io/github/license/jnonino/control-tower-docker-image)](https://github.com/jnonino/control-tower-docker-image)
[![](https://img.shields.io/github/issues/jnonino/control-tower-docker-image)](https://github.com/jnonino/control-tower-docker-image)
[![](https://img.shields.io/github/issues-closed/jnonino/control-tower-docker-image)](https://github.com/jnonino/control-tower-docker-image)
[![](https://img.shields.io/github/languages/code-size/jnonino/control-tower-docker-image)](https://github.com/jnonino/control-tower-docker-image)
[![](https://img.shields.io/github/repo-size/jnonino/control-tower-docker-image)](https://github.com/jnonino/control-tower-docker-image)

## How to use Control Tower

Run the container

        docker run --tty --interactive \ 
        -env AWS_ACCESS_KEY_ID='<YOUR_AWS_ACCESS_KEY>' \
        -env AWS_SECRET_ACCESS_KEY='<YOUR_AWS_SECRET_KEY>' \
        --name control-tower \
        jnonino/control-tower \
        bash

After running that command you will prompted to the container environment, you can run the following Control Tower commands:

- **deploy**: Deploys or updates a Concourse ([Documentation](https://github.com/EngineerBetter/control-tower/blob/master/docs/deploy.md))
- **destroy**: Destroys a Concourse ([Documentation](https://github.com/EngineerBetter/control-tower/blob/master/docs/destroy.md))
- **info**: Fetches information on a deployed environment ([Documentation](https://github.com/EngineerBetter/control-tower/blob/master/docs/info.md))
- **maintain**: Handles maintenance operations in control-tower ([Documentation](https://github.com/EngineerBetter/control-tower/blob/master/docs/maintain.md))
- **help**: Get help for commands

More information [here](https://github.com/EngineerBetter/control-tower)
