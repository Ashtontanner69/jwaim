# jwaim
this is a cheat for the 64 bit linux csgo (tested on ubuntu 14.04, 16.04, and 17.04)


install additional dependencies:
```bash
apt-get install libboost-all-dev libx11-dev libx11-dev:i386 libxtst-dev libconfig++-dev build-essential qt5-default
```

how to build:

install the dependencies (above).

navigate to the base directory (usually ~/jwaim).

run command:
```bash
qmake ./jwaim.pro
```
run command: 
```bash
make
```
rename settings-example.cfg to settings.cfg and modify settings to your liking.

run jwaim as super user:

```bash 
gksudo ./jwaim
```


NOTE:
please make sure you have settings.cfg in the same directory as your current working directory (when you execute the application), otherwise you will experience problems with libconfig.
