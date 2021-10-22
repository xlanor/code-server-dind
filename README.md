# code-server-dind

Based on the [linuxserver](https://hub.docker.com/r/linuxserver/code-server) packaged image.

Adds an additional docker installation and provides a docker-compose file with the host-mounted daemon

execute `sudo chmod 666 /var/run/docker.sock` after launching to fix user permissions.

Mainly for GIOS where all the work is done in docker and I need to move between different machines.

