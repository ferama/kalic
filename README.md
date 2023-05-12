# kalic

A docker based, persistent (through chroot) kali environment.

Edit the envirnment on docker-compose.yml.

Bring up with:

```
docker-compose up -d
```

Wait some time (half an hour? less?) to let the chroot environment build
Look at the logs with

```
docker-compose logs -f
```
Access the the kali container using:

* ssh on `SSHD_LISTEN_ADDRESS`
* vnc on `VNCPORT`
* with browser on http://host:NOVNCPORT/vnc.html


