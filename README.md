# pantheon
Pantheon of Congestion Control
==============================

Make
----

0. Get submodules:
```
$ git submodule init
$ git submodule update
```
or clone this project with the --recursive option

0. Run the following commands to make:
```
$ mkdir build
$ cd build
$ cmake .. && make
```

Usage
-----
To use default TCP as congestion control:
```
$ ./server TCP
$ ./client TCP 0.0.0.0
```
