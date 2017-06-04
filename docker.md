## Docker

#### Run a container with interactive shell
`docker run -ti --name=mycentos centos:latest /bin/bash`

#### Run a container in the background
`docker run -d --name=mynginx nginx:latest`

#### Run a container using the host's network
`docker run -d --name=mynginx --net=host nginx:latest`

#### Build a container from a Dockerfile that is in your current directory
`docker build -t my-nginx .`

#### Tag a container
`docker tag my-nginx docker.example.com/my-nginx:0.1`
`docker tag docker.example.com/my-nginx:0.1 docker.example.com/my-nginx:latest`

#### Push container to repository
`docker push docker.example.com/my-nginx:0.1`

#### Run docker container with bash as entry point
`docker run -i --entrypoint /bin/bash -t <image name>`

#### List volumes of a container
`docker inspect <CONTAINER ID> | jq '.[] | {Volumes: .Volumes, VolumesRW: .VolumesRW}'`

#### Remove stopped containers
```docker rm -v `docker ps -a -q -f status=exited` ```
