
# Doom 2022
Fork of https://github.com/id-Software/DOOM.
Some bugs are fixed so it can be compiled in 2022. 

Compile on Ubuntu 16.04 32 bit system.

```
# to compile 
mkdir linux
sudo apt-get install libx11-dev libxext-dev

make all

# to execute 
sudo apt-get install xserver-xephyr openbox

Xephyr :1 -ac -screen 1000x700x8 &
DISPLAY=:1 openbox &
DISPLAY=:1 ./linuxxdoom
```
