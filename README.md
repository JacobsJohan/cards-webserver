# Description

The goal of this repository is to create a webserver that hosts card games to play with your
friends. The idea is to run this webserver on an embedded device like a Raspberry Pi or a Beaglebone
for example. This means it must be easy to cross-compile the code and distribute it to the embedded
target. These embedded devices will typically always run a Linux OS, but it should also be possible
to set everything up on an x86 Windows or Linux device (not a hard requirement at the moment).

**Note: this project is still in its very early stages. Expect a lot of bugs and very little
functionality**

## Overview

- Provide server side functionality using the Django framework in Python.

## Security

The provided webserver will initially run in a local home network, but in the end it will be
publicly available such that your friends can connect to the server. This means that security will
play an important role in this project and must be researched thoroughly.

## Disclaimer

The goal of this project is to create a stable, configurable, locally hosted webserver to play games
with friends. It is not the intention to offend anyone or violate any copyrights.
