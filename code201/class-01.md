# Reading Notes-01

JavaScript allows a page to react

## Clients and Servers

- Clients make requests to servers
- Servers create responses and send them to the client
- Internet connection allows a client to connect to the world
- TCP/IP
  - Transmission Control Protocol and Internet Protocol
  - Defines how the data should travel
- DNS
  - Domain Name System
  - This acts as an address book for websites
  - browsers will attempt to find the IP address before retrieving the website
- HTTP
  - Hypertext Transfer Protocol
  - This acts as the common language between the client and server
- Component files
  - Consist of: Code files, and Assets
    - Code files
      - HTML, CSS, and JavaScript
      - Others may be included
    - Assets
      - Images, music, video, Word documents, and PDFs

## What happens

1. Browser checks the DNS
2. Browser sends HTTP request to the server, asking for copy of the site
   - This uses TCP/IP settings to send
3. The server responds, and begins sending the data packets
4. The browser then assembles the packets into the page and displays it

## Parse order

1. link and script elements, both send request to the server for the specified file
2. Browser generates an in-memory DOM from the HTML
   - Generates an in-memory CSSOM from the CSS
   - Compiles and executes the JavaScript
3. Browser then builds the page
   - DOM
   - CSSOM
   - executes the JavaScript

## Planning

1. Subject
2. Details
3. Basic design

## Assets

- Text
- Theme color
- Images
- Font

## Scripts

- Used script tags in the body of the HTML document to alter the page prior to displaying it to the user
- querySelector() grabs a chosen reference and stores it
- textContent selects the textContent property
- Variables in JavaScript can reference any object, and be changed repeatedly
- Events can be attached to elements to trigger actions
  - Such as swapping an image onclick

## Getting Started

1. Poem<br/ > a request is sent<br/ >  the server receives it now<br/ >  it returns a page

2. The browser requests the script and link files describing the page's scripts and CSS and uses the HTML to assemble the page with CSS and scripts
3. find image, add to images folder
4. a string is identified by 'quotes' a number has no ''
5. a variable is a reference to an object, variables can be operated on

## Introduction to HTML

1. Information about an element
2. an open tag content and a close tag
3. an article is a the main portion with sections as dividers possibly contained in the article
4. HTML tags, head tags, meta tags, title tags, body tags
5. metadata allows a search engine to identify important information about the page without needing to process all the data
6. it can be used to identify information that isn't elsewhere on the DOM

## How to start to design a Website

1. Planning is always the first step
2. What do you want to share

## Semantics

1. h1 is the standard element for top level headings
2. Information can be better identified by importance

## What is JavaScript?

1. altering a page after it reaches the client and allowing the site to be reactive to a users action
2. adding a script tag in the body will include it in the page
