# DockerFil
https://roadmap.sh/projects/basic-dockerfile
git clone https://github.com/TalalNuman/hello-docker.git
cd hello-docker
docker build -t hello-captain.
docker run hello-captain
RUN
FROM alpine:latest
ENV MYNAME="Amir"
CMD ["sh", "-c", "Yell Hello $MYNAME"]
