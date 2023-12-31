# Project Docker Todo List

#### Based on front-end, back-end & its tests a container is used to creat a connection between these three segments.

* Designed by using Docker

### Commands
* The following docker commands are used and can be found in `./docker/docker-commands`:

  | Command     | Description |
  | ----------- | ----------- |
  | 1   | Creating a container using `alpine` image version `3.12` interactively w/o execution, naming it `01container` |
  | 2   | Initialize container `01container` |
  | 3   | List all containers, filtering by name `01container` |
  | 4   | Run the `cat /etc/os-release` command on container `01container` without attaching to it |
  | 5   | Remove container `01container` |
  | 6   | Realize download of `nginx` image with version `1.21.3-alpine` |
  | 7   | Initialize a new container with the `nginx` image version `1.21.3-alpine`: in background, naming it `02images` and running on port 3000 |
  | 8   | Stop container `02images` |
  | 9   | Generate a build from the back-end Dockerfile, naming the image `todobackend` |
  | 10  | Generate a build from the front-end Dockerfile, naming the image `todofrontend` |
  | 11  | Generate a build from the tests Dockerfile, naming the image `todotests` |
  | 12  | Create a docker-compose for communication between the `back-end`, `front-end` and `tests` |
