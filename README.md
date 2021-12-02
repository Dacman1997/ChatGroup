# ChatGroup

For the Group Messenger each client should be connected to the server via TCP/IP.
Next, all the clients should have an ID to make possible create a chat with particular clients.
When a client is create, he should can comunicate with the server by a client-services protocol.
Every message exchanges between client and server contain a key, so the client-services protocol depends on key to identify the operation that
server should perform.

Commands:

./send.out "message" "key"

./list.clients - List client name and ID

"key":

send_all

send_private <client_ID1> <client_ID2> ...

disconnect
