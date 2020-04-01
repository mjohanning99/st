# Marvin's fork of suckless' st
This is my fork of suckless' simple terminal (st for short). It includes pywal, has the patch applied for scrolling through the history (with vim controls) and a bunch of other stuff.

## Prerequisites
You will need the Xlib header files for building the application; but they should already be installed on your machine if you're running GNU/Linux. I also use pywal for setting the color theme, you will therefore need to install pywal and run it at least once. Then open the `config.h` file and change the path at the top to your local user's one.

## Installation
You can edit the `config.mk` if you wish to change the setup according to your needs (it defaults to installing to /usr/local). 
Afterwards, you can simply run `make clean install`
