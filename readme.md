docker build -t alpine-test .
docker images
docker run -d -p 8080:8080 alpine-test
docker ps -a
docker exec -it <containerID> /bin/bash