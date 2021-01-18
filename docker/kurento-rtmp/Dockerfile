FROM debian:stable-20210111

ARG DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y npm vim lsof ffmpeg

ENTRYPOINT ["tail", "-f", "/dev/null"]
