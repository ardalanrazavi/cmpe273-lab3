# cmpe273-lab3

**What happened when you send message from client in Multicast UDP when server is not available?**

Since, the client is also listening on the same multicast port and address, it will receive its own datagram which was sent to the multicast address.