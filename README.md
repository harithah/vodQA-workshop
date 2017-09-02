# Template for vodQA workshop

commands:
docker ps

docker images

docker networks ls

docker inspect <>

docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)
docker ps -a | grep "selenium" | awk '{print $1}' |xargs docker rm -f

docker images -f dangling=true
docker rmi $(docker images -f dangling=true -q)
docker rm $(docker ps -a -f status=exited -q)


docker volume ls

docker volume rm volume_name volume_name

docker volume rm $(docker volume ls -f dangling=true -q)

docker rm -v container_name