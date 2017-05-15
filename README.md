# Multiplayer Snakes Game

## Requirements
This program uses Berkeley sockets, and only functions properly on terminals in a Unix environment. Make sure you also have `ncurses` installed. Run 

```
sudo apt-get install ncurses-dev
```	 
in a terminal window to install it.

### Instructions
Clone the repository and run *make* to generate the server and client programs. Run the server (occupying port 7070) on a machine which is accessible to all clients. 

Clients connect to the server by running `./client <server-ip>` in a terminal window, whose size is at least 80 × 24. 
