# NP_Lab_CourseProject
Implement simple file server using sockets. The file server should be able to take the request from any client and return the requested file to client or return error message, status to client. Consider all the possible inputs for the file server. Implement using programming. Compare this result with FTP by using suitable tools.

Server
The server performs the following functions.

Start the program.

Declare the variables and structures required.

The socket is created using the socket function.

The socket is binded to the specific port.

Start listening for the connections.

Accept the connection from the client.

Creates a child process to handle request client among multiple clients.

Close server socket descriptor

Create a new file. 10. Receives the data from the client.

Write the data into the file.

The program is stopped.

Client
The client performs the following functions.

Start the program

Declare the variables and structures required.

A socket is created and the connect function is executed.

The file is opened.

The data from the file is read and sent to the server.

The socket is closed.

The program is stopped
