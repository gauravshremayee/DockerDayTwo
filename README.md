# DockerDayTwo

#Docker start and Stop container 

$docker start containerId
$docker stop containerid

#Share Desktop to Container 

$docker run -it -v ~/Desktop:/Desktop r-base bash

#Docker copy files
#find docker id
docker ps -a
docker cp foo.txt containerid:/path


