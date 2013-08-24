lightum-indicator
=================

Indicator for Lightum light sensor daemon

(c)2012 Pau Oliva Fora - pof[at]eslack(.)org


This is a simple indicator applet that allows users of [lightum](https://github.com/poliva/lightum) to control it from the panel.

It also has profile management, so you can save different profiles and switch between them quickly.

## Screenshot
![alt text](https://github.com/poliva/lightum-indicator/raw/master/icons/lightum-indicator.png "lightum-indicator screenshot")

## Ubuntu Pakcages
Official Ubuntu packages are available in [poliva/lightum-mba ppa](https://launchpad.net/~poliva/+archive/lightum-mba):

     sudo add-apt-repository ppa:poliva/lightum-mba
     sudo apt-get update
     sudo apt-get install lightum-indicator

## Installing from source
(tested on Ubuntu 13.04)

1. Clone the repository by running ```git clone https://github.com/poliva/lightum-indicator``` and ```cd``` into the project's directory.
2. Run ```sudo make install```
