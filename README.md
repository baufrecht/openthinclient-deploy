tcos-dev
========

container for developing tcos packages

requirements
============

- docker

installation
============

manual way:

1. clone the git repo to "$some_place"
2. cd "$some_place"

```
docker build -t tcos-dev:latest .
```
-or-

from docker hub:
```
docker pull steffenhoenig/tcos-dev
```
source tcosdev.rc

```
D [optional docker options]
```
-or-
```
Z [optional docker options]
D = interactive development profile
Z = starts sshd and is meant for services
```

full installation guide 
============
A full package development guide can be found in our wiki.

http://wiki.openthinclient.org/wiki/Pakete-Entwickeln/en
