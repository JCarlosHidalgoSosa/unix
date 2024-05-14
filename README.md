# Unix server

This repo contains two implementation of a server: One using a web framework and the other no.

Important is the own implementation:
- Open terminal at "own_implementation" directory
- Compile code with 

```
gcc unixserver.c -o unixserver

```
This will execute a web game on port 8080 and server on 8090
Server port and route of directory to serve html can be modified on unixserver.conf file

TODO
- Implement redirections between own server and game server.