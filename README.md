# docker-utility-scripts

Collection of utility script for docker command.

## Why do we need this?
Has it ever happened that you are running same docker command again and again? It happens with me a lot. After working on various images and containers for dev/test/build, my list of images and containers keep growing. Once in a while i do clean up of these to free up the disk space. But running `docker images`, `docker ps`, `docker ps -a`, `docker image rm`, `docker rmi ` on & on is painful. So, i wrote few tiny scripts to run these commands based on passed argument/filters. 

Currently docker has limited support of filters like `until` or `label`. For ex: check for filters in [container_prune](https://docs.docker.com/engine/reference/commandline/container_prune/) or [image_prune](https://docs.docker.com/engine/reference/commandline/image_prune/) .

## How to use it?
