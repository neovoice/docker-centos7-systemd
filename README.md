# docker-centos7-systemd
Centos 7 docker with systemd enabled

This docker is based on centos 7's official docker with systemd

### Pull image:

docker pull etates/centos7-systemd:latest


## Run container:

**docker run -d --name centos-systemd -v /sys/fs/cgroup:/sys/fs/cgroup:ro --tmpfs /run -v /etc/localtime:/etc/localtime:ro etates/centos7-systemd:latest**
