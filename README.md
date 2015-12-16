Keepass2 (password manager) in a Docker
=====================

Run:
----

* Allow X11 connections: `xhost +local:docker`
* Run command:
```bash
docker run -ti --rm     -v /tmp/.X11-unix:/tmp/.X11-unix      -v $HOME/Documents:/root/Documents      -e DISPLAY=unix$DISPLAY      --name keepass2      kvaps/keepass2
```
