## Running a basic nginx dockerfile (without any dockerfiles)

docker run -p 9020:80 nginx


## Running the alpine container with a dockerfile

1. docker build -t alpine-test .
2. docker images
3. docker run -d -p 8080:8080 alpine-test
4. docker ps -a
5. docker exec -it <containerID> /bin/bash