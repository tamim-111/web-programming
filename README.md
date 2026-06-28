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
- [2. Chapter 2:](#2-chapter-2)
  - [2.1. Table, Form, Hyperlink, Images, Lists (How Those Tags Work):](#21-table-form-hyperlink-images-lists-how-those-tags-work)
    - [2.1.1. Table:](#211-table)
    - [2.1.2. Form:](#212-form)
    - [2.1.3. Hyperlink:](#213-hyperlink)
    - [2.1.4. Images:](#214-images)
    - [2.1.5. Lists:](#215-lists)
  - [2.2. Difference Between Block and Inline Elements:](#22-difference-between-block-and-inline-elements)
    - [2.2.1. Block Elements:](#221-block-elements)
    - [2.2.2. Inline Elements:](#222-inline-elements)
    - [2.2.3. Block and Inline example:](#223-block-and-inline-example)
  - [2.3. HTML Semantic Elements:](#23-html-semantic-elements)
- [3. Chapter 3:](#3-chapter-3)
  - [3.1. CSS Selectors (Element, Class, and ID):](#31-css-selectors-element-class-and-id)
    - [3.1.1. Element Selector:](#311-element-selector)
    - [3.1.2. Class Selector:](#312-class-selector)
    - [3.1.3. ID Selector:](#313-id-selector)
  - [3.2. CSS Display Property:](#32-css-display-property)
    - [3.2.1. display: block:](#321-display-block)
    - [3.2.2. display: inline:](#322-display-inline)
    - [3.2.3. display: inline-block:](#323-display-inline-block)
    - [3.2.4. display: none:](#324-display-none)
    - [3.2.5. Summary:](#325-summary)
  - [3.3. CSS Position Property:](#33-css-position-property)
    - [3.3.1. position: static:](#331-position-static)
    - [3.3.2. position: relative:](#332-position-relative)
    - [3.3.3. position: absolute:](#333-position-absolute)
    - [3.3.4. position: sticky:](#334-position-sticky)
    - [3.3.5. position: fixed:](#335-position-fixed)
  - [3.4. CSS Grid and Flexbox:](#34-css-grid-and-flexbox)
    - [3.4.1. CSS Flexbox:](#341-css-flexbox)
    - [3.4.2. CSS Grid:](#342-css-grid)
    - [3.4.3. Grid vs Flexbox:](#343-grid-vs-flexbox)
  - [3.5. CSS Media Queries:](#35-css-media-queries)
  - [3.6. CSS Viewport:](#36-css-viewport)
    - [3.6.1. Viewport Units:](#361-viewport-units)
    - [3.6.2. Examples:](#362-examples)
  - [3.7. How to add CSS:](#37-how-to-add-css)
  - [3.8. Box Model:](#38-box-model)
  - [3.9. Border:](#39-border)
  - [3.10. CSS Background:](#310-css-background)
- [Question:](#question)
  - [1(a) Compare Internet and Extranet based on purpose, accessibility, and security:](#1a-compare-internet-and-extranet-based-on-purpose-accessibility-and-security)
  - [1(b) Differentiate between a Web Server and a Web Client in terms of function and operation:](#1b-differentiate-between-a-web-server-and-a-web-client-in-terms-of-function-and-operation)
  - [1(c) Analyze the sequence of events that occurs when a new URL is entered into a web browser and the web page is displayed:](#1c-analyze-the-sequence-of-events-that-occurs-when-a-new-url-is-entered-into-a-web-browser-and-the-web-page-is-displayed)
  - [1(d) Demonstrate the use of HTML attributes in `<img>`, `<a>`, and `<form>` elements:](#1d-demonstrate-the-use-of-html-attributes-in-img-a-and-form-elements)
    - [`<img>`:](#img)
    - [`<a>`:](#a)
    - [`<form>`:](#form)
  - [2(a) Write HTML code for the following table:](#2a-write-html-code-for-the-following-table)
  - [2(b) Write HTML code for the following list.](#2b-write-html-code-for-the-following-list)
  - [3(a) Define CSS and explain the types of CSS. Show proper examples:](#3a-define-css-and-explain-the-types-of-css-show-proper-examples)
  - [3(b) Apply different CSS selectors (element, class, ID) to style various parts of an HTML document:](#3b-apply-different-css-selectors-element-class-id-to-style-various-parts-of-an-html-document)
  - [3(c) Design a CSS rule that sets the background image of a webpage as paper.png, makes it fixed, and positions it in the bottom-right corner without repeating:](#3c-design-a-css-rule-that-sets-the-background-image-of-a-webpage-as-paperpng-makes-it-fixed-and-positions-it-in-the-bottom-right-corner-without-repeating)
  - [4(a):](#4a)
  - [4(b) Explain the use of background-clip property with a gradient image background. Also show another useful usage:](#4b-explain-the-use-of-background-clip-property-with-a-gradient-image-background-also-show-another-useful-usage)
    - [Example 1: Gradient Text:](#example-1-gradient-text)
    - [Example 2: background-clip: content-box:](#example-2-background-clip-content-box)


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

# 2. Chapter 2: 

## 2.1. Table, Form, Hyperlink, Images, Lists (How Those Tags Work):

### 2.1.1. Table: 
A table is used to organize and display data in rows and columns.

Common Tags that are used to create a tables:
- `<table>` → Creates the table.
- `<tr>` → Table row.
- `<th>` → Table heading.
- `<td>` → Table data (cell).

```html
<table border="1">
  <tr>
    <th>Column 1</th>
    <th>Column 2</th>
  </tr>
  <tr>
    <td>Row 1, Column 1</td>
    <td>Row 1, Column 2</td>
  </tr>
  <tr>
    <td>Row 2, Column 1</td>
    <td>Row 2, Column 2</td>
  </tr>
</table>
```

![alt text](./assets/images/chapter-2/table.png)

### 2.1.2. Form:
A form is used to collect user input, such as login information, registration details, or feedback.

Common Tags that are used to create a form:
- `<form>` → Creates the form.
- `<input>` → Input field.
- `<input type="radio">` → Radio button field.
- `<label>` → Label for the input field.
- `<textarea>` → Textarea field.
- `<select>` → Dropdown field.
- `<button>` → Button field.

```html
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        <br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email">
        <br><br>

        <label for="message">Message:</label>
        <textarea id="message" name="message"></textarea>
        <br><br>

        <label for="country">Country:</label>
        <select id="country" name="country">
            <option value="us">United States</option>
            <option value="ca">Canada</option>
            <option value="uk">United Kingdom</option>
        </select>
        <br><br>

        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label>
        <br><br>

        <button type="submit">Submit</button>
    </form>
```

![alt text](./assets/images/chapter-2/form.png)

### 2.1.3. Hyperlink:
A hyperlink connects one web page or resource to another. It is created using the <a> (anchor) tag.

Common Attributes that are used to create a hyperlink:
- `href` → Specifies the URL of the page the link goes to.
- `target` → Specifies where to open the linked document (e.g., `_blank` for a new tab, `_self(default)` for the same tab).

```html
<a href="https://www.example.com" target="_blank">Visit Example</a>
```
![alt text](./assets/images/chapter-2/hyperlink.png)

### 2.1.4. Images:
An image is a visual representation that can be displayed on a web page. It is added using the <img> tag.

Common Attributes that are used to create an image:
- `src` → Specifies the path to the image file.
- `alt` → Specifies an alternative text for the image if the image cannot be displayed.

```html
<img src="./imageName.jpg" alt="Description of the image">
```

Note: If we have nested folder then follow the folder order: 
```html
<img src="./assets/images/chapter-2/table.png" alt="Description of the image">
```

### 2.1.5. Lists:
A list is a collection of items that can be displayed in an ordered or unordered manner.    

Common Tags that are used to create a list:
- `<ul>` → Unordered list.
- `<ol>` → Ordered list.
- `<li>` → List item.

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>

<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>
```

![alt text](./assets/images/chapter-2/lists.png)


Note: Nested lists can be created by placing one list inside another list item.

```html
<ul>
  <li>Item 1</li>
  <li>Item 2
    <ul>
      <li>Subitem 2.1</li>
      <li>Subitem 2.2</li>
    </ul>
  </li>
  <li>Item 3</li>
</ul>
```

## 2.2. Difference Between Block and Inline Elements:
HTML elements are mainly divided into Block and Inline elements based on how they are displayed on a web page.

| Block Elements                             | Inline Elements                        |
| ------------------------------------------ | -------------------------------------- |
| Starts on a new line                       | Does not start on a new line           |
| Takes the full available width             | Does not take the full available width |
| Can contain both block and inline elements | Can only contain inline elements       |

### 2.2.1. Block Elements: 
A block element starts on a new line and takes up the full width available by default.

Characteristics:
- Starts on a new line.
- Takes the full available width.
- Can contain both block and inline elements.

Examples: 
```html
<div>
<p>
<h1> to <h6>
<section>
<article>
<ul>
<ol>
<table>
<form>
```

### 2.2.2. Inline Elements: 
An inline element does not start on a new line and takes up only the width necessary for its content.

Characteristics:
- Does not start on a new line.
- Does not take the full available width.
- Can only contain inline elements.

Examples: 
```html
<span>
<a>
<img>
<strong>
```

### 2.2.3. Block and Inline example: 

```html
<div>
  <p>This is a <strong>block</strong> element.</p>
  <span>This is an inline element.</span>
  <a href="#">This is another inline element.</a>
</div>
```

![alt text](./assets/images/chapter-2/block-vs-inline.png)

## 2.3. HTML Semantic Elements:  
https://github.com/muhammad-tamim/html-notes#html-semantic-elements

# 3. Chapter 3:
## 3.1. CSS Selectors (Element, Class, and ID):
A CSS selector is used to select HTML elements so that CSS styles can be applied to them.

The three most common selectors are:
- Element Selector
- Class Selector
- ID Selector

### 3.1.1. Element Selector:
An element selector selects all HTML elements of the same type.

- html
```html
<p>First paragraph</p> 
<p>Second paragraph</p>
```
- css
```css
p {
  color: red;
}
```

### 3.1.2. Class Selector:
A class selector selects one or more elements that have the same class name. It starts with a dot (.).

- html
```html
<p class="paragraph">First paragraph</p> 
<p class="paragraph">Second paragraph</p>
```
- css
```css
.paragraph {
  color: blue;
}
```

### 3.1.3. ID Selector:
An ID selector selects one unique element with a specific ID. It starts with a hash (#).

Note: An ID should be unique and used only once on a page.

- html

```html
<p id="paragraph">First paragraph</p>
```

- css

```css
#paragraph {
  color: green;
}
```

## 3.2. CSS Display Property:
The display property controls how an HTML element is displayed on a web page. It determines whether an element appears as a block, inline, inline-block, or none (hidden).

Common Values:
- block
- inline
- inline-block
- none

### 3.2.1. display: block:
Behaves like a block element. 

- html

```html
<span>This is an inline element.</span>
<span>This is an inline element.</span>
<span>This is an inline element.</span>
```

![alt text](./assets/images/chapter-3/display-block-1.png)

- css

```css
span {
  display: block;
}
```

![alt text](./assets/images/chapter-3/display-block-2.png)

### 3.2.2. display: inline:
Behaves like an inline element.

- html

```html
<p>This is an block element.</p>
<p>This is an block element.</p>
<p>This is an block element.</p>
```
![alt text](./assets/images/chapter-3/display-inline-1.png)

- css

```css
p {
  display: inline;
}
```
![alt text](./assets/images/chapter-3/display-inline-2.png)   

### 3.2.3. display: inline-block:
An inline-block element:
  - Stays on the same line like an inline element.
  - Allows you to set width and height like a block element.

**Before Applying:**

- html

```html
<span>This is an inline element.</span>
<span>This is an inline element.</span>
<span>This is an inline element.</span>
```
![alt text](image.png)
![alt text](./assets/images/chapter-3/display-inline-block-1.png)

- css

```css
span {
  display: inline; /*Default for span element*/
  width: 150px;
  height: 50px;
}
```

**After Applying:**

- html

```html
<span>This is an inline element.</span>
<span>This is an inline element.</span>
<span>This is an inline element.</span>
```
![alt text](./assets/images/chapter-3/display-inline-block-1.png)

- css

```css
span {
  display: inline-block;
  width: 150px;
  height: 50px;
}
```

![alt text](./assets/images/chapter-3/display-inline-block-2.png)


### 3.2.4. display: none: 
used to hide an element from the web page.

- html
  
```html
<p>This element will be hidden</p>
```  

- css

```css
p {
  display: none;
}
```

### 3.2.5. Summary: 

| Display Value | New Line? | Takes Full Width? | Width & Height Work? |
| ------------- | --------- | ----------------- | -------------------- |
| block         | ✅ Yes     | ✅ Yes             | ✅ Yes                |
| inline        | ❌ No      | ❌ No              | ❌ Usually No         |
| inline-block  | ❌ No      | ❌ No              | ✅ Yes                |
| none          | ❌ Hidden  | ❌ No              | ❌ Not displayed      |

## 3.3. CSS Position Property:
The position property determines how an HTML element is positioned on a web page. There are 5 values on the position property:
- Static → Default position.
- Relative → Move from its original position.
- Absolute → Position relative to the nearest positioned parent.
- Fixed → Fixed to the browser window.
- Sticky → Acts like relative, then sticks while scrolling.


### 3.3.1. position: static:
https://github.com/muhammad-tamim/css-notes#1401-staticdefault

### 3.3.2. position: relative:
https://github.com/muhammad-tamim/css-notes#1402-relative

### 3.3.3. position: absolute:
https://github.com/muhammad-tamim/css-notes#1403-absolute

### 3.3.4. position: sticky:
https://github.com/muhammad-tamim/css-notes#1404-sticky

### 3.3.5. position: fixed:
https://github.com/muhammad-tamim/css-notes#1405-fixed

## 3.4. CSS Grid and Flexbox: 
CSS Grid and Flexbox are CSS layout systems used to arrange and align elements on a web page.
- Flexbox is designed for one-dimensional layouts (either a row or a column).
- CSS Grid is designed for two-dimensional layouts (rows and columns).

### 3.4.1. CSS Flexbox: 
Common Flexbox Properties: 

| Property        | Purpose                   |
| --------------- | ------------------------- |
| display: flex   | Creates a flex container  |
| flex-direction  | Sets row or column layout |
| justify-content | Aligns items horizontally |
| align-items     | Aligns items vertically   |
| gap             | Adds space between items  |

```html
    <div class="container">
        <div class="item">1</div>
        <div class="item">2</div>
        <div class="item">3</div>
        <div class="item">4</div>
    </div>
```

```css
        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 10px;
        }

        .item {
            background-color: lightblue;
            padding: 20px;
            text-align: center;
        }
```

![alt text](./assets/images/chapter-3/flex.png)

### 3.4.2. CSS Grid: 
Common Grid Properties: 

| Property              | Purpose                       |
| --------------------- | ----------------------------- |
| display: grid         | Creates a grid container      |
| grid-template-columns | Defines the columns           |
| gap                   | Adds space between grid items |
| justify-items         | Aligns items horizontally     |
| align-items           | Aligns items vertically       |


```html
<div class="container">
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
    <div class="item">4</div>
</div>
```

```css
.container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    justify-items: center;
    align-items: center;
    gap: 10px;
}

.item {
    background-color: lightblue;
    padding: 20px;
    text-align: center;
}
```
  
![alt text](./assets/images/chapter-3/grid.png)



### 3.4.3. Grid vs Flexbox: 

| Flexbox                                  | Grid                                         |
| ---------------------------------------- | -------------------------------------------- |
| One-dimensional layout                   | Two-dimensional layout                       |
| Arranges items in a row or column        | Arranges items in rows and columns           |
| Best for menus, navigation bars, buttons | Best for page layouts, dashboards, galleries |
| Easier for small layouts                 | Better for complex layouts                   |


## 3.5. CSS Media Queries:
https://github.com/muhammad-tamim/css-notes#19-media-queries

## 3.6. CSS Viewport:  
The viewport is the visible area of a web page in the browser. The viewport size changes depending on the device: 
- Desktop → Large viewport
- Tablet → Medium viewport
- Mobile → Small viewport

Note: Responsive websites use the viewport to adjust their layout for different screen sizes.

### 3.6.1. Viewport Units: 

| Unit | Meaning                              |
| ---- | ------------------------------------ |
| vw   | 1% of the viewport width             |
| vh   | 1% of the viewport height            |
| vmin | 1% of the smaller viewport dimension |
| vmax | 1% of the larger viewport dimension  |

### 3.6.2. Examples:

1. Full Screen Height:

here, the The element takes 100% of the viewport height
```css
.hero { 
  height: 100vh; 
}
```

2. Half Screen Width: 

here, the The element takes 50% of the viewport width
```css
.box {
   width: 50vw; 
}  
```


## 3.7. How to add CSS: 
https://github.com/muhammad-tamim/css-notes#13-different-ways-to-add-css

## 3.8. Box Model: 
https://github.com/muhammad-tamim/css-notes#8-box-modal

## 3.9. Border: 
https://github.com/muhammad-tamim/css-notes#6-border

## 3.10. CSS Background:
https://github.com/muhammad-tamim/css-notes#9-background-properties


# Question:
## 1(a) Compare Internet and Extranet based on purpose, accessibility, and security:
| Feature           | Internet                                          | Extranet                                                                                                              |
| ----------------- | ------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| **Purpose**       | Used for sharing information publicly.            | Used for secure communication between an organization and authorized external users (customers, suppliers, partners). |
| **Accessibility** | Anyone with an internet connection can access it. | Only authorized users with login credentials can access it.                                                           |
| **Security**      | Less secure because it is open to everyone.       | More secure because access is restricted and protected by authentication.                                             |

## 1(b) Differentiate between a Web Server and a Web Client in terms of function and operation: 
| Web Server                              | Web Client                                       |
| --------------------------------------- | ------------------------------------------------ |
| Stores website files and data.          | Requests and displays web pages.                 |
| Receives HTTP requests from clients.    | Sends HTTP requests to servers.                  |
| Processes requests and sends responses. | Receives responses and shows them to users.      |
| Example: Apache, Nginx.                 | Example: Google Chrome, Firefox, Microsoft Edge. |

## 1(c) Analyze the sequence of events that occurs when a new URL is entered into a web browser and the web page is displayed:

- The user enters a URL into the browser.
- The browser checks the DNS to find the website's IP address.
- The browser connects to the web server using TCP/IP.
- The browser sends an HTTP/HTTPS request.
- The web server processes the request.
- The server sends back HTML, CSS, JavaScript, and other files.
- The browser downloads these files.
- The browser renders (displays) the web page to the user.

## 1(d) Demonstrate the use of HTML attributes in `<img>`, `<a>`, and `<form>` elements:

### `<img>`:

`<img src="flower.jpg" alt="Flower" width="300" height="200">`

here, 
- src → Image location
- alt → Alternative text
- width → Image width
- height → Image height

### `<a>`:

`<a href="https://www.example.com" target="_blank" >Click Here</a>`
here, 
- href → Destination URL
- target="_blank" → Opens the link in a new tab

### `<form>`:
A form is used to collect user input, such as login information, registration details, or feedback.

Common Tags that are used to create a form:
- `<form>` → Creates the form.
- `<input>` → Input field.
- `<input type="radio">` → Radio button field.
- `<label>` → Label for the input field.
- `<textarea>` → Textarea field.
- `<select>` → Dropdown field.
- `<button>` → Button field.

```html
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        <br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email">
        <br><br>

        <label for="message">Message:</label>
        <textarea id="message" name="message"></textarea>
        <br><br>

        <label for="country">Country:</label>
        <select id="country" name="country">
            <option value="us">United States</option>
            <option value="ca">Canada</option>
            <option value="uk">United Kingdom</option>
        </select>
        <br><br>

        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label>
        <br><br>

        <button type="submit">Submit</button>
    </form>
```

![alt text](./assets/images/chapter-2/form.png)

## 2(a) Write HTML code for the following table: 

![alt text](./assets/images/section-a/table.png)

```css
        table {
            width: 600px;
            border-collapse: collapse;
        }

        th,
        td {
            border: 1px solid black;
            padding: 8px;
        }
```

```html
 <table>
        <tr>
            <th colspan="2">Name</th>
            <th>Class</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>Anna</td>
            <td>10</td>
            <td>A</td>
            <td>anna@mail.com</td>
        </tr>
        <tr>
            <td>John</td>
            <td>9</td>
            <td>B</td>
            <td>john@mail.com</td>
        </tr>
        <tr>
            <td>Sara</td>
            <td>10</td>
            <td>A</td>
            <td>sara@mail.com</td>
        </tr>
        <tr>
            <td>Tuhin</td>
            <td>8</td>
            <td>A</td>
            <td>tuhin@mail.com</td>
        </tr>
    </table>
```

## 2(b) Write HTML code for the following list.

```html
    <ul>
        <li>Web Design
            <ol>
                <li>HTML
                    <ol type="a">
                        <li>Tags</li>
                        <li>Attributes</li>
                    </ol>
                </li>

                <li>CSS
                    <ol type="a">
                        <li>Selectors</li>
                        <li>Colors</li>
                    </ol>
                </li>
            </ol>
        </li>

        <li>Programming
            <ol>
                <li>JavaScript
                    <ol type="a">
                        <li>Variables</li>
                        <li>Functions</li>
                    </ol>
                </li>
            </ol>
        </li>
    </ul>
```


## 3(a) Define CSS and explain the types of CSS. Show proper examples:
CSS (Cascading Style Sheets) is a stylesheet language used to control the appearance of HTML elements, such as colors, fonts, spacing, layout, and positioning.

There are three types of CSS:

https://github.com/muhammad-tamim/css-notes#13-different-ways-to-add-css

## 3(b) Apply different CSS selectors (element, class, ID) to style various parts of an HTML document: 
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        /* Element Selector */
        h1 {
            color: blue;
        }

        /* Class Selector */
        .text {
            color: green;
            font-size: 20px;
        }

        /* ID Selector */
        #title {
            background: yellow;
        }
    </style>
</head>

<body>
    <h1 id="title">Welcome</h1>

    <p class="text">
        This paragraph uses a class selector.
    </p>

    <p>
        This paragraph is normal.
    </p>
</body>

</html>
```

## 3(c) Design a CSS rule that sets the background image of a webpage as paper.png, makes it fixed, and positions it in the bottom-right corner without repeating: 

```css
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            background-image: url("paper.png");
            background-repeat: no-repeat;
            background-position: bottom right;
            background-attachment: fixed;
        }
    </style>
</head>

<body>
    <h1>Background Example</h1>
</body>

</html>
```

Explanation
- background-image → Sets the image.
- background-repeat: no-repeat → Prevents repeating.
- background-position: bottom right → Places image at the bottom-right.
- background-attachment: fixed → Keeps image fixed while scrolling.

## 4(a): 
![alt text](./assets/images/question/4a-question.png)

```html
<!-- index.html -->
 <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="parent">

        <div class="fixed">
            Fixed Div
        </div>

        <div class="sticky">
            Sticky Div
        </div>

        <div class="relative">
            Relative Div
        </div>

    </div>

</body>

</html>
```

```css
/* style.css */

.parent{
    height:300px;
    width:100%;
    border:2px solid black;
}

.fixed{
    position:fixed;
    top:0;
    background:red;
    color:white;
}

.sticky{
    position:sticky;
    top:100px;
    background:green;
    color:white;
}

.relative{
    position:relative;
    width:100px;
    height:200px;
    overflow:auto;
    background:lightblue;
}
```

## 4(b) Explain the use of background-clip property with a gradient image background. Also show another useful usage:
The background-clip property specifies how far the background extends within an element. 

Common values:
- border-box (default): The background extends to the outer edge of the border.
- padding-box: The background extends to the edge of the padding.
- content-box: The background extends to the edge of the content.
- text: The background is clipped to the text content.
  
### Example 1: Gradient Text: 


```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1 {
            background: linear-gradient(red, blue);
            color: transparent;
        }
    </style>
</head>

<body>
    <h1>Gradient Text</h1>

</body>

</html>
```

### Example 2: background-clip: content-box: 

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        div {
            border: 10px solid black;
            padding: 20px;
            background: orange;
            background-clip: content-box;
        }
    </style>
</head>

<body>
    <div>
        This is a content-box example.
    </div>
</body>

</html>
```
