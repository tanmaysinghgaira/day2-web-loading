# Day 2 – Website Loading Process

## Website tested
shorterloop.com

## DNS Lookup

nslookup shorterloop.com → 76.76.21.21
dig shorterloop.com +short → 76.76.21.21

## Network Requests Observed

### 1) GET /
- Status: 200 OK
- Type: document
- Header: content-type: text/html

### 2) GET /_next/static/...
- Status: 200 OK
- Type: script
- Header: content-type: application/javascript

### 3) GET /images/...
- Status: 200 OK
- Type: image
- Header: content-type: image/webp

### 4) GET /favicon.ico
- Status: 200 OK
- Type: image
- Header: content-type: image/x-icon

### 5) GET /styles.css
- Status: 200 OK
- Type: stylesheet
- Header: content-type: text/css

## What I understood
When we enter a website URL:
1. DNS converts domain name into IP address.
2. Browser opens a TCP connection.
3. TLS secures the connection if HTTPS is used.
4. Browser sends HTTP request.
5. Server sends response files like HTML, CSS, JS, images.
6. Browser renders the page on screen.
