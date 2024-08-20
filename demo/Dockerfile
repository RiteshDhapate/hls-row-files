FROM ubuntu

RUN /usr/bin/apt-get update && \
    /usr/bin/apt-get upgrade -y && \
    /usr/bin/apt-get install -y  ffmpeg

WORKDIR /home/app

ENTRYPOINT [ "bash" ]