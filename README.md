This is a basic network-analyzer/packet sniffer I am working on.

It contains 2 branches:
  1. The main branch has a default version so to speak, in which I've set the sockets to AF_INET and IPPROTO_IP.
  2. The second one, is as it's name suggests, with the sockets set to AF_PACKET and ntohs(0x0003).
  
To run just symply run it in CLI like this:
  python [insert desired name here].py

Start browsing the internet with the sniffer on and you will see all the packets being captured.
