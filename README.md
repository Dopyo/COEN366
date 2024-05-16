PROJECT DONE

1. Introduction
The project consists of implementing in, Java, C++, or Python, a Peer-to-Peer File System
(P2FS), over UDP and TCP. 

2. Peer to Peer File System (P2FS)
The Peer-to-Peer File System (P2FS) consists of several clients and one server. The main goal
of the P2FS is to allow for users (clients/peers) to share files. For the project we are dealing
only with text files.
The role of the server is to keep track of the registered clients (peers), how they can be
reached and the list of files available from each one of them. It will use this information to
inform the clients about each whenever needed.
The communications between the clients (peers) and the server is through UDP, while the
communication between the clients (peers) is through UDP at the beginning, but file transfer
must be through TCP.
In the following we assume one user per client and therefore we use the terms user, client and
peer interchangeably. 
