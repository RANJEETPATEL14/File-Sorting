# File-Sorting
This application is for sorting a file. Server will ask the client to upload the file to sort.
The Server and Client must have separate directories. Process will be aborted after every
upload/download. It displays the files present in the server directory, and allows the client to
select from them.

For Server:
javac TCPServer.java
java TCPServer <server directory name>

For Client:
javac TCPClient.java
java TCPClient <client directory name>
