# Terminal Talk

### A simple instant messaging program written in python

![Python](https://img.shields.io/badge/Language-Python%203+-yellow) ![Tkinter](https://img.shields.io/badge/GUI-Tkinter-success)

## GUI Implementation

- Simple GUI for client has been implemented by using python tkinter module

![Terminal talk GUI](https://github.com/siva222r/terminaltalk/blob/master/screenshots/terminaltalk.png?raw=true)

## Usage Guide

- Run the server script on the machine you have designated as the host
- the ip address of that machine will appear
- now run the client program which will ask for an IP address of the host / server
- enter the IP address seen on the Host machine
- you should now be connected and able to communicate over the internet!!

## Whats Coming Up:
- End to End Encryption
- GUI for both server and Client
- Speed Up the code a bit
- tidy up Variables


## Customization

- If you Want more connections to the server, feel free to modify the "serversocket.listen(10)" code, the ten represents that only 10 unique IP addresses can connect to this server, the higher you put it though the more recource hungry it can become.
- The Server Program Automatically finds the IP address that it has been designated from the router, however you can change this if you like to a static IP address or Local Host for debugging. Change "serversocket.bind((ip_address, 9985))" ip_address to "xxx.xxx.xx.xxx".

## Problem Shooting

- If your having trouble connecting, try opening port 9985 for both inbound and outbound connections, this should solve any issues.
- this **REQUIRES** Python 3.
