Welcome to docker-raumserver
===================
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/ChriD/)
[![Docker Pulls](https://img.shields.io/docker/pulls/chris/docker-raumserver.svg)](https://registry.hub.docker.com/u/chrid/docker-raumserver/)


Raumserver is a HTTP REST API nodeJs library for controling the Raumfeld Multiroom System via simple HTTP commands.  
(see https://github.com/ChriD/node-raumserver).


Installation
-------------

Search for **docker-raumserver** and install it.  
You have to use `net=--host` for the container, otherwise the raumserver will not find any devices.  
Docker raumserver will reside on **port 8585**  


Additional Info
-------------
Currently it works well on a QNAP NAS but not on any Windows Docker installation  
***Use 'net=--host' !!!***

