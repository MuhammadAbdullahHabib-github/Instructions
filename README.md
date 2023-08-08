### Dockerfile Instructions

**FROM Command**
<br>
`FROM <image>:<tag>`
<br>
An `image` will be from docker hub or local reops and `tag` will be the version of image.


- example -> FROM Node:16
+ example ->  FROM myregistry.example.com/myimage:latest
 

 ##### Create Image Out of Dockerfile

 `docker build -t <name> .`

 + `-t tag for new namee`
 - `. is showing current file`

#### Checking Procss Status
`docker ps -a`
+ `ps -> process state`
- `-a flag for all`
```
 CONTAINER ID   IMAGE                COMMAND           CREATED         STATUS                      PORTS                 NAMES
abcdef123456   nginx:latest         "nginx -g 'daemon…"  2 hours ago    Exited (0) 2 hours ago                           inspiring_elion
ghijkl789012   postgres:12.5        "docker-entrypoint…" 3 days ago     Up 3 days                                        pensive_hopper
```
##### The `docker images` command is used to list all the Docker images that are currently present on your system.
### RUN DOCKER IMAGE -> Container
`docker run -it --name <container name> <image>  /bin/bash/`
When you use /bin/bash in various contexts, you're essentially instructing the system to run the Bash shell
