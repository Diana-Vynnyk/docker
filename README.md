# docker
```bash
docker ps -a                # Lists containers (and tells you which images they are spun from)

docker images               # Lists images 

docker rm <container_id>    # Removes a stopped container

docker rm -f <container_id> # Forces the removal of a running container (uses SIGKILL)

docker rmi <image_id>       # Removes an image or docker image rm <image_id>
                            # Will fail if there is a running instance of that image i.e. container

docker rmi -f <image_id>    # Forces removal of image even if it is referenced in multiple repositories, 
                            # i.e. same image id given multiple names/tags 
                            # Will still fail if there is a docker container referencing image
```
