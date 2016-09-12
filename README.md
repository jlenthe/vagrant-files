# vagrant-files

## Overview
This project is a collection of Vagrant configuration and supporting files for running various server applications using vagrant.

The idea is to have a set of vagrant configuration files for various databases, web servers, message brokers, etc so you don't need to 
have them installed on you computer all the time.  You can use vagrant to fire up a virtual machine for running the application
and then throw it away when your done.

## Environments 

Each environment includes a Debian GNU/Linux server running 64 bit Jessie.  The server application of interest is automatically
started on the server when it starts.  The ports for the application of interest are forwarded from the host to guest. 

### ActiveMQ 

After doing _vagrant up_ you have ActiveMQ 5.14 with the following ports available:

  * Admin web access on 8161
  * Openwire on port 61616
  * AMQP on port 5672
  * STOMP on port 61613
  * MQTT on port 1883
  * WS on port 61614

The admin account is 'admin' and the password is 'admin'. 
 

### Jenkins

### MongoDB

### MySQL

### PostgreSQL

### Tomcat
