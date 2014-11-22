Hide and seek protocol
====

When the client connects to a new network

Then it opens a pub socket and send a hello message to every ip address

The content of the message is

"found ya"

The server should reply to the client with the secret and shut down.
The server must only reply to the first connecting client & only the first client.
