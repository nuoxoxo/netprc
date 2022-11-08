- 4-Layer Inter Model

&nbsp; | &nbsp;
------ | ------ 
&nbsp; | $\color{SeaGreen}\text{ (Internet) }$
1      | $\color{YellowOrange}\text{ Link Layer }$
2      | $\color{YellowOrange}\text{ Network Layer }$
3      | $\color{YellowOrange}\text{ Transport Layer }$
4      | $\color{YellowOrange}\text{ Application Layer }$
&nbsp; | $\color{SeaGreen}\text{ (User) }$

- $\color {Cerulean} \text { Internet\ addresses } $
  - The Internet Protocol (IP) uses a 32-bit, 2-part address field.
    - $\color{YellowOrange}\text{ 32-bit }$ \
    An IPv4 address has 32-bits, limiting the capacity to 4294967296 (2^32) addresses
    - $\color{YellowOrange}\text{ 2-part }$ \
    An IP address is a combination of the _host_ and _network_ address
- $\color {Cerulean} \text { Subnet\ addresses } $
  - Subnet addressing allows an autonomous system made up of multiple networks to share the same Internet address. 
- $\color{Cerulean}\text{ Broadcast\ addresses }$
  - The TCP/IP can send data to all hosts on a local network or to all hosts on 
all directly connected networks. Such transmissions are called broadcast messages. 
- $\color{Cerulean}\text{ Local\ loopback\ addresses }$
  - The Internet Protocol defines the special network address, 127.0.0.1, as a local loopback address
- $\color{Cerulean}\text{TCP}$ - $\color{YellowOrange}\text{ What\ is\ it? }$
  - TCP stands for Transmission Control Protocol
  - It is a communications standard to send packets across the internet
  - TCP organizes data so that it can be transmitted between a server and a client.
  - It is one of the basic protocols to ensures end-to-end data delivery.
- $\color{Cerulean}\text{TCP}$ - $\color{YellowOrange}\text{What\ does\ it\ do?}$
  - TCP establishes a connection between a source and its destination before data is transmitted 
  - The connection remains _Live_ until communication begins.
  - TCP breaks large amounts of data into smaller packets
  - It guarantees the integrity of the data being communicated.
- $\color{Cerulean}\text{TCP}$ - $\color{YellowOrange}\text{ Who\ are\ using\ TCP? }$
  - peer-to-peer sharing methods like File Transfer Protocol (FTP)
  - Secure Shell (SSH)
  - Telnet
  - Email protocols like Internet Message Access Protocol (IMAP)
  - Post Office Protocol (POP)
  - Simple Mail Transfer Protocol (SMTP)
  - Web access, like the Hypertext Transfer Protocol (HTTP)
