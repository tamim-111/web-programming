<h1 align="center">Web Programming</h1>

- [1. chapter 1:](#1-chapter-1)
  - [1.1. TCP, IP, Protocols (How it works):](#11-tcp-ip-protocols-how-it-works)
    - [1.1.1. What is a Protocol:](#111-what-is-a-protocol)
    - [1.1.2. TCP/IP (Transmission Control Protocol / Internet Protocol):](#112-tcpip-transmission-control-protocol--internet-protocol)
      - [1.1.2.1. TCP (Transmission Control Protocol):](#1121-tcp-transmission-control-protocol)
      - [1.1.2.2. IP (Internet Protocol):](#1122-ip-internet-protocol)
    - [1.1.3. How TCP and IP Work Together:](#113-how-tcp-and-ip-work-together)
  - [1.2. DNS Process:](#12-dns-process)
    - [1.2.1. What is DNS:](#121-what-is-dns)
    - [1.2.2. How DNS Works:](#122-how-dns-works)
  - [1.3. Web Accessibility:](#13-web-accessibility)
    - [1.3.1. What is Web Accessibility:](#131-what-is-web-accessibility)
    - [1.3.2. Why is Web Accessibility Important:](#132-why-is-web-accessibility-important)
    - [1.3.3. Common Accessibility Features:](#133-common-accessibility-features)
  - [1.4. Web Clients and Web Servers:](#14-web-clients-and-web-servers)
    - [1.4.1. What is a Web Client:](#141-what-is-a-web-client)
    - [1.4.2. What is a Web Server:](#142-what-is-a-web-server)
    - [1.4.3. How They Work Together:](#143-how-they-work-together)


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

## 1.2. DNS Process:
### 1.2.1. What is DNS:
DNS (Domain Name System) is the phonebook of the Internet. It translates a domain name (such as www.google.com) into an IP address that computers use to communicate. Without DNS, you would have to remember IP addresses instead of website names.

### 1.2.2. How DNS Works: 
Suppose you type `www.google.com` in your browser: 

```
User types: www.google.com 
    │ 
    ▼ 
Browser sends DNS request 
    │ 
    ▼ 
DNS Server (Finds the IP address) 
    │ 
    ▼ 
Returns IP Address 
    │ 
    ▼ 
Browser connects to Google's Server 
    │ 
    ▼ 
Web page is displayeds
```

## 1.3. Web Accessibility: 
### 1.3.1. What is Web Accessibility:
Web Accessibility means designing and developing websites so that everyone, including people with disabilities, can access and use them easily.

### 1.3.2. Why is Web Accessibility Important: 
- Makes websites usable for everyone.
- Helps people with visual, hearing, physical, or cognitive disabilities.
- Improves the overall user experience.
- In many countries, accessibility is required by law.

### 1.3.3. Common Accessibility Features: 
- Alternative text (alt text) for images.
  - `<img src="image.jpg" alt="Description of the image">`
- Screen reader support for visually impaired users.
  - `<a href="page.html" aria-label="Go to the next page">Next</a>`
- Good color contrast between text and background.
  - `<body style="background-color: gray; color: black;">`
- Use of clear headings and proper HTML structure.
  - `<h1>Main Heading</h1>, <h2>Subheading</h2>`
- Descriptive link text (e.g., "Download PDF" instead of "Click here").
  - `<a href="file.pdf">Download PDF</a>`

## 1.4. Web Clients and Web Servers:
### 1.4.1. What is a Web Client:
A Web Client is a program or device that requests information from a web server. The most common web client is a web browser like Google Chrome, Mozilla Firefox, or Microsoft Edge.

### 1.4.2. What is a Web Server:
A Web Server is a computer or software that stores websites and responds to requests from web clients. The most common web server software includes Apache, Nginx, and Microsoft IIS.

### 1.4.3. How They Work Together:

```
User 
    │ 
    ▼ 
Web Client (Browser) 
    │ 
    ▼
Web Server 
    │ 
    ▼ 
Returns HTML, CSS, JavaScript, Images, etc. 
    │ 
    ▼ 
Browser Displays the Website
```
