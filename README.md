# Quotes-Server
This is a C program that serves motivational quotes to a client through named pipes (FIFOs).
The client file creates its own named pipe, sends the pipe's name to the server, and then opens the server's named pipe to request and receive motivational quotes
