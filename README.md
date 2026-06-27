<h1 align="center">Web Programming</h1>

- [chapter 1:](#chapter-1)
  - [TCP, IP, Protocols (How it works):](#tcp-ip-protocols-how-it-works)
    - [What is a Protocol:](#what-is-a-protocol)
    - [TCP/IP (Transmission Control Protocol / Internet Protocol):](#tcpip-transmission-control-protocol--internet-protocol)
      - [TCP (Transmission Control Protocol):](#tcp-transmission-control-protocol)
      - [IP (Internet Protocol):](#ip-internet-protocol)
    - [How TCP and IP Work Together:](#how-tcp-and-ip-work-together)


# chapter 1:
## TCP, IP, Protocols (How it works):
### What is a Protocol: 
A protocol is a set of rules that devices follow to communicate with each other over a network. Examples of protocols is TCP, IP, HTTP, HTTPS, FTP

### TCP/IP (Transmission Control Protocol / Internet Protocol):
TCP/IP is the standard communication protocol used on the Internet.

Note:
- TCP = Breaks, checks, and rebuilds the data.
- IP = Finds where the data should go.

#### TCP (Transmission Control Protocol):
TCP is responsible for:
- Breaking data into small pieces called packets
- Checking that packets arrive correctly
- Requesting missing or damaged packets again
- Reassembling the packets into the original data

#### IP (Internet Protocol):
IP is responsible for:
- Giving every device an IP address
- Sending packets to the correct destination

### How TCP and IP Work Together:
Suppose you open `www.google.com`:
- Step 1: Your browser sends a request to the server.
- Step 2 (TCP): TCP breaks the request into small packets and numbers them.
- Step 3 (IP): IP adds the source and destination IP addresses and sends the packets across the Internet.
- Step 4: Routers forward the packets until they reach Google's server.
- Step 5: The server sends the response back using the same process.
- Step 6 (TCP): TCP checks that every packet arrived correctly, requests any missing packets, and puts them back together to display the web page.

Summary: 
```
Browser
   |
   |
TCP → Breaks data into packets        
   |
   |
IP → Adds addresses and sends packets
   |
   |
Internet (Routers)
   |
   |
Server
   |
   |
TCP → Reassembles packets
   |
   |
Web page is displayed      
```