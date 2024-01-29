## INTRODUCTION
when a device is connected to the internet, it’s assigned an IP address. This is composed of 4 sets of numbers, from 0 to 255. The starting 2 set of numbers are reserved for local networks.
The local network is created by your Wi-Fi/Ethernet router which is connected to internet provider. You can communicate between devices on your local network, but you cannot communicate with devices in other local networks. This is because there is a level of protection. In a local network, the IP address is private.
A server is a computer whose job is to serve us something. It's IP address is public.
DNS servers have the job of mapping a domain name to an IP address. 
The language that computers use to talk to each other is called a protocol. The IP protocol part is what I mentioned above; IP addresses and so on. That’s the base layer that identifies how computers can find each other.
On top of that layer, we have what we call transport protocols. They define how computers send packets of data to each other. Transmission Control Protocol makes sure packets are delivered from the client to the server, and from the server to the client.
## WHAT IS URL
The string that we type to ask the browser to fetch a page from a server is called as URL.
The first part of the URL i.e., http:// or https:// determines the protocol. Then we have the server address, which can be a domain name or an IP i.e., google.com or 142.251.209.14. Anything appended to the address part represents the document path.
The web server is responsible for interpreting the request and, once analyzed, serving the correct response back to the client.
## WHAT IS A PORT
When making network requests, you use an IP address, or a host name, and a port. For example, http://localhost:8080, here it used port 8080.
Port is a technique introduced to allow multiple applications to respond on the same computer, on the same protocol. If we have a web server running on our machine, then a second web server can be started on a different port.
The programs can use any unused port between 1 and 65535 
## THE DNS PROTOCOL 
The system that maps domain names to IP addresses is called DNS: Domain Name System. It's a network of servers. 
The system is organized like a tree. There is one DNS server at the top, called root DNS server. It knows the IP address of the DNS servers that are managing each domain extension, like com, net, org and so on, including the country-specific domain extensions and the new ones like blog, dev or tech.
## THE TCP PROTOCOL
TCP is connection-oriented. Before transmission can happen over TCP, a connection must be established. Data is sent, in form of little packets, and when the communication ends the connection is closed. 
Defined in [RFC 793](https://tools.ietf.org/html/rfc793) in 1981, TCP is one of the oldest pillars of the Internet.
When data is transmitted over TCP, handshake that must happen. this handshake allows the end-to-end connection to happen, and this makes sure TCP can provide one of its peculiar features: reliability.
In TCP, a connection happens from process to process, using the concept of ports. Each application protocol has a default port.
## THE UDP PROTOCOL
UDP, User Datagram Protocol, is a transfer protocol. It is connectionless. UDP was defined in [RFC 768](https://tools.ietf.org/html/rfc768) in 1980.
It is faster because, each packet sent is more lightweight, as it does not contain all the information needed in TCP. It does not have a lighter handshake process. But, UDP is not reliable as TCP.
In UDP, there is no built-in check to control if a packet was received, and if it is received correctly. It uses ports to allow communication between processes.
Some of the most notable application protocols that rely on the UDP layer are DNS and DHCP, and more importantly is the base layer of HTTP/3, the next version of HTTP.
