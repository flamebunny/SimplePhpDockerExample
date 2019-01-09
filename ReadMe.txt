docker commands:
docker container ls
docker container stop dockername


docker build -t hello-world
docker run -p 8080:80 hello-world
docker run -p 8080:80 -v c:/projects/docker/src/:/var/www/html/ hello-world