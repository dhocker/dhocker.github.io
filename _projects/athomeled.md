---
layout: project
title: AtHomeLED - Addressable LED light strip server
---

Repo: [https://github.com/dhocker/athomeled](https://github.com/dhocker/athomeled)

The AtHomeLED server is designed to run simple LED strip light shows on a Raspberry Pi. 
The original motive for the AtHomeLED server was for something to run a holiday 
lighting program on a strip of C9 LED lights.

The server can be controlled locally or remotely via a TCP based communication 
interface (the remote control interface). The interface is suited to command-line 
control via telnet or a front-end client application that uses the interface as an API.

A show is constructed as a script using a relatively simple scripting language 
(Script Engine). Scripts are stored in script files in the ScriptFileDirectory 
on the AtHomeLED host.

Using the remote control interface you can:

* view a list of available script files
* start a script file
* stop the currently running script file
* view the status of the AtHomeLED server

There are several different kinds of LED strips depending on which controller 
string is used. AtHomeLED supports the following.

* WS2811 based LED strings
* APA102 (SPI protocol) based LED strips (e.g. Adafruit DotStars)

How to wire these to a Raspberry Pi is out of the scope of this document, 
but examples of how to wire these strings can be found in the 
[references](https://github.com/dhocker/athomeled/blob/master/README.md#references).

AtHomeLED comes with a driver for the both of these LED strings. 
If you want to use another LED string type you will need to write your own driver. 
The AtHomeLED/driver/dummy_driver.py file provides a template for implementing a driver. 
The DUMMY driver can be used as a mock device. This is a good solution for testing.
