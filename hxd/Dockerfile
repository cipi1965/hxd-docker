FROM debian:buster
COPY . /bin
WORKDIR /data
RUN apt-get update -y
RUN apt-get install -y libncurses6
CMD /bin/hxd -c /data/hxd.conf
