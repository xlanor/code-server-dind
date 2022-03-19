# code-server-dind

Based on the [linuxserver](https://hub.docker.com/r/linuxserver/code-server) packaged image.

Adds an additional docker installation and provides a docker-compose file with the host-mounted daemon. This allows you to use docker directly from code-server's terminal.

execute `sudo chmod 666 /var/run/docker.sock` after launching to fix user permissions.

Mainly for GIOS where all the work is done in docker and I need to move between different machines. I prefer to have a web interface to allow me to write code on my ipad/mac/linux device while still maintaining the same environment. 

