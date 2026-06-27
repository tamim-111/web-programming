<h1 align="center">Web Programming</h1>

- [1. Introduction to the Internet and World Wide Web](#1-introduction-to-the-internet-and-world-wide-web)
  - [1.1. The Internet:](#11-the-internet)
  - [1.2. From fARPANET to Today:](#12-from-farpanet-to-today)
  - [1.3. Birth of The Web:](#13-birth-of-the-web)
  - [1.4. Who Runs The Internet:](#14-who-runs-the-internet)
  - [1.5. Intranets and Extranets:](#15-intranets-and-extranets)
  - [1.6. What is a Network:](#16-what-is-a-network)
  - [1.7. Components of a Network:](#17-components-of-a-network)
  - [1.8. Types of Networks:](#18-types-of-networks)
  - [1.9. TCP/IP (Transmission Control Protocol / Internet Protocol):](#19-tcpip-transmission-control-protocol--internet-protocol)
    - [1.9.1. TCP (Transmission Control Protocol):](#191-tcp-transmission-control-protocol)
    - [1.9.2. IP (Internet Protocol):](#192-ip-internet-protocol)
  - [URIs and URLs](#uris-and-urls)
    - [URI (Uniform Resource Identifier)](#uri-uniform-resource-identifier)
    - [URL (Uniform Resource Locator):](#url-uniform-resource-locator)


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