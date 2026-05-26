<h1 align="center">DMconnect</h1>

DMconnect is a **decentralized** messenger for legacy systems with encryption capabilities.

It uses a **federated** architecture, similar to email, allowing multiple servers to seamlessly communicate with each other.

The protocol itself is [designed to be as simple as possible](http://dmconnectspec.w10.site), so you can maintain communication using a regular Telnet client. Of course, you are free to create separate client applications.

## Clients
Currently, there are clients for:
- Windows 9x ([ExTO](https://github.com/Archie-boop/ExTO), [YADC](https://yadc.w10.site) and others, [see the full list of clients on the website](http://dmconnect.w10.site/download.html)).
- J2ME ([DMobile](https://github.com/tankwars92/DMobile)).
- Linux ([Dsconnect](http://dsconnect.w10.site)).

## More about DMconnect
More information about DMconnect:  
- [Protocol specification](http://dmconnectspec.w10.site/) – description of the DMconnect client-server protocol
- [Extension documentation](https://dmconnect.github.io) – DMconnect extension protocol (**DXP**) documentation
- [Official website](http://dmconnect.w10.site/) – official DMconnect website

### How to understand that your own DMconnect client is ready to use?

Your client is considered ready for DMconnect usage if it supports the following:

1. Ability to properly work with UTF-8 text encoding.
2. Ability to send and receive messages through a TCP connection.
3. Ability to periodically send keep-alive packets to maintain the connection.

DMconnect is intentionally designed to be a very simple protocol. In its basic form, it is simply an exchange of text messages between a client and a server over TCP.
