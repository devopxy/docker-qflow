
## This container runs

* [Xvfb](http://www.x.org/releases/X11R7.6/doc/man/man1/Xvfb.1.xhtml) - X11 in a virtual framebuffer
* [x11vnc](http://www.karlrunge.com/x11vnc/) - A VNC server that scrapes the above X11 server
* [noNVC](https://kanaka.github.io/noVNC/) - A HTML5 canvas vnc viewer
* [Fluxbox](http://www.fluxbox.org/) - a small window manager
* [qflow](http://opencircuitdesign.com/qflow/) - A complete VLSI Synthesis to GDSII tool-chain

### With Docker Hub

* `docker pull devopxy/qflow-novnc`
* `docker run -p 8083:8083 -ti  qflow-novnc:latest`
