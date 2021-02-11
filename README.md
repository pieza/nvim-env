docker build -t nvim-env .
docker run -it nvim-env bash

## Win10 alias
`doskey devp=docker run -it --volume="%cd%:/home/$DOCKER_USER/workspace" --workdir="/home/$DOCKER_USER/workspace" nvim-env bash`