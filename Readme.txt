In this current fast pacing world, chat applications are the current era of the communication. Secure chat has secure end to end message delivery system with the help of AES cryptography. This project is intended to stress out the importance of encryption of data to prevent them for getting stolen or being eavesdropped by illegal parties.

USAGE
This server can be set up on a local area network by choosing any on computer to be a server node, and using that computer’s private IP address as the server IP address and an unused port. Care must be taken to choose a port that is currently not in usage. For example, port 22 is default for ssh, and port 80 is default for HTTP protocols. So, these two ports preferably, shouldn’t be used or reconfigured to make them free for usage.
Server sets a password for additional security. Clients should authenticate themselves with the password while connecting to server. 
When a client sends a message to server, the message will be encrypted on client side using AES algorithm. The server decrypts the message and sends it to all the clients except to the one who sent it. By this way clients can communicate themselves.

Thanks to Hemanth and Sri Sai for the project idea