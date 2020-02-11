# -public-docker-commands
various useful docker commands and or snippets of information aimed at getting Docker/Lucee/NGinx/MuraCMS on Digital Ocean running. Use at your own risk.

To list all running and stopped containers
# docker ps -a
show only their container id
# docker ps -aq

To remove all containers that are NOT running (usefulfor local dev to get rid of artefacts
# docker rm "`docker ps -aq -f status=exited`"
