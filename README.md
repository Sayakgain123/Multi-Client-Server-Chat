Group chat program where there is a single server and multiple clients. The server forwards a client's message to all the other clients.

Platform: Linux with GCC compiler

Compiling: gcc filename.c -pthread

Running the server: ./a.out portnumber

Running the clients: ./a.out username portnumber

Stopping the clients and server: CTRL-D

Note: The portnumber provided to clients should be same as the one given to server. Username is just an identity of yourself.
