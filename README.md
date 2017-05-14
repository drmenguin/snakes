# Multiplayer Snakes Game

## Description
This game is a programming assignment for [CPS2003: Systems Programming](http://www.um.edu.mt/ict/studyunit/CPS2003), a course forming part of my B.Sc. in Mathematics and Computer Science. 

## Requirements
This program uses [Berkeley sockets](https://en.wikipedia.org/wiki/Berkeley_sockets), and therefore only functions properly on terminals in a Unix environment. Check whether you have `ncurses` installed, by running

```
apt -qq list ncurses-bin ncurses-base
``` 
in a terminal window. If `ncurses` is present, the output should produce two lines with the tag `[installed]` at the end. If no output is produces, then `ncurses` is not present and you need to install it by running
```
sudo apt-get install ncurses-dev
```
in a terminal window.

## Instructions
Clone the repository and run *make* to generate the server and client programs. Run the server (occupying port 7070) on a machine which is accessible to all clients. 

Clients connect to the server by running `./client <server-ip>` in a terminal window, whose size is at least 80 × 24. 

