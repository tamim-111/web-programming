<h1 align="center">Web Programming</h1>

- [1. chapter 1:](#1-chapter-1)
  - [1.1. TCP, IP, Protocols (How it works):](#11-tcp-ip-protocols-how-it-works)
    - [1.1.1. What is a Protocol:](#111-what-is-a-protocol)
    - [1.1.2. TCP/IP (Transmission Control Protocol / Internet Protocol):](#112-tcpip-transmission-control-protocol--internet-protocol)
      - [1.1.2.1. TCP (Transmission Control Protocol):](#1121-tcp-transmission-control-protocol)
      - [1.1.2.2. IP (Internet Protocol):](#1122-ip-internet-protocol)
    - [1.1.3. How TCP and IP Work Together:](#113-how-tcp-and-ip-work-together)


# 1. chapter 1:
## 1.1. TCP, IP, Protocols (How it works):
### 1.1.1. What is a Protocol: 
A protocol is a set of rules that devices follow to communicate with each other over a network. Examples of protocols is TCP, IP, HTTP, HTTPS, FTP

### 1.1.2. TCP/IP (Transmission Control Protocol / Internet Protocol):
TCP/IP is the standard communication protocol used on the Internet.

Note:
- TCP = Breaks, checks, and rebuilds the data.
- IP = Finds where the data should go.

#### 1.1.2.1. TCP (Transmission Control Protocol):
TCP is responsible for:
- Breaking data into small pieces called packets
- Checking that packets arrive correctly
- Requesting missing or damaged packets again
- Reassembling the packets into the original data

#### 1.1.2.2. IP (Internet Protocol):
IP is responsible for:
- Giving every device an IP address
- Sending packets to the correct destination

### 1.1.3. How TCP and IP Work Together:
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