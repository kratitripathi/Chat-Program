# Chat-Program
A chat program in Eclipse using sockets

Chat communication is the process of exchanging messages between two systems continuously. Both systems come with the same responsibilities:  
1.	Reading from the keyboard. Uses an input stream like BufferedReader connected to System.in.  
2.	Sending data read from the keyboard to the other system. Uses an output stream like PrintWriter connected to getOutputStream() method of Socket.  
3.	Receiving data from the other system. Uses an input stream like BufferedReader connected to getInputStream() method of Socket.  
As the responsibilities are same, both client and server programs contain the same stream objects and same code. The order of using stream objects varies in the while loop. The chat ends when the client sends “Bye” to the server.

