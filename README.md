docker-firefox-openjdk
==

For all you lost souls which are forced to use java applets - Let... there... be... light for you!

Run `docker-compose up` to start firefox-esr with a working openjdk-8-jre plugin and enjoy.

### Requirements
* `docker`
* `docker-compose` 
* Running X11


### Issues

* In case you receive an `connection refused` error - this might be because you need to add your hostname to the hosts allowed to connect to the X server. You can do this by executing ``xhost +`hostname -s` `` 
