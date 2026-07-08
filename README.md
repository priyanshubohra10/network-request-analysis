# Network Requests Analysis

## Website Visited

https://shorterloop.com

---

## Network Requests

### 1. GET /

* **Type:** Document
* **Status Code:** 200 OK
* **Header:** `Content-Type: text/html; charset=utf-8`

This is the main HTML page of the website. The browser loads this page first.

---

### 2. GET /assets/scripts/lozad.min.js

* **Type:** Script
* **Status Code:** 200 OK
* **Header:** `Content-Type: text/javascript; charset=utf-8`

This JavaScript file helps load website content efficiently.

---

### 3. GET /assets/css/fonts.css

* **Type:** Stylesheet
* **Status Code:** 200 OK
* **Header:** `Content-Type: text/css; charset=utf-8`

This CSS file contains the font styles used on the website.

---

### 4. GET /assets/css/main.css

* **Type:** Stylesheet
* **Status Code:** 200 OK
* **Header:** `Content-Type: text/css; charset=utf-8`

This file contains the main styling and layout of the website.

---

### 5. GET /assets/fonts/geist-sans/Geist-Regular.woff2

* **Type:** Font
* **Status Code:** 200 OK
* **Header:** `Content-Type: font/woff2`

This font file is used to display the website text correctly.

---

## DNS Lookup

### Command Used

```bash
nslookup shorterloop.com
```

### Output

```text
Server:  UnKnown
Address: 10.146.168.49

Non-authoritative answer:
Name:    shorterloop.com
Address: 199.36.158.100
```

---

## Screenshots

* `network.png` – Network tab showing the requests made while loading the website.
* `terminal.png` – Output of the `nslookup` command.

---

## What I Learned

* A website is made up of multiple files such as HTML, CSS, JavaScript, fonts, and images.
* The browser sends a separate request for each file needed to load the webpage.
* DNS converts a domain name into an IP address.
* A **200 OK** status code means the request was successful.
* Response headers provide information about the content returned by the server.
