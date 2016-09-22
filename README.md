# docker-template
Docker and Compose templates for learners of programming 

CREATE A DIR IN LOCAL MACHINE    TO DELETE A DIRECTORY   TO DELETE A NON-EMPTY DIRECTORY
$   mkdir "DIRNAME"               $ rmdir "Dirname"       $ sudo rm -rf "DIR NAME"

INIT GIT 
$ git init

PULL THE FILE
$ git pull "URL"

TO START CONTAINER         TO SEE THE CONTAINER        TO STOP CONTAINER                       TO REMOVE CONTAINERS PERMANENTLY
$ docker-compose up -d      $ docker ps -a           $ docker stop $(docker ps -a -q)            $ docker rm $(docker ps -a -q)

TO SEE THE IMAGES           TO REMOVE IMAGES                 TO REMOVE IMAGES FORCE
$ docker images            $ docker rmi <image id>         $ docker rmi -f <image id>

$ docker exec -it container-jdk /bin/bash

TO RUN FILE
./gradlew run


