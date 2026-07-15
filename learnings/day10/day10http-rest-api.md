# HTTP Standards & REST APIs

## What is HTTP?

HTTP (HyperText Transfer Protocol) is the communication protocol used between a client and a server. Whenever a user visits a website or sends data through a web application, HTTP is responsible for transferring that data.

Example:
- Browser requests a webpage.
- Server processes the request.
- Server sends a response back to the browser.

---

# Client and Server

**Client**
- Browser
- Mobile App
- Desktop Application

**Server**
- Stores data
- Processes requests
- Sends responses

Communication Flow:

Client → HTTP Request → Server

Server → HTTP Response → Client

---

# HTTP Request

An HTTP request contains:

- Method
- URL
- Headers
- Body (optional)

Example:

GET /users

---

# HTTP Response

An HTTP response contains:

- Status Code
- Headers
- Response Body

Example:

```json
{
  "message": "Success"
}
```

---

# HTTP Methods

## GET

Used to retrieve data.

Example:

GET /users

---

## POST

Used to create new data.

Example:

POST /users

---

## PUT

Replaces an existing resource completely.

Example:

PUT /users/1

---

## PATCH

Updates only selected fields.

Example:

PATCH /users/1

---

## DELETE

Deletes a resource.

Example:

DELETE /users/1

---

# HTTP Status Codes

## 200 OK

Request completed successfully.

## 201 Created

Resource created successfully.

## 400 Bad Request

Client sent an invalid request.

## 401 Unauthorized

Authentication required.

## 403 Forbidden

Permission denied.

## 404 Not Found

Requested resource does not exist.

## 500 Internal Server Error

Unexpected server error.

---

# What is REST?

REST (Representational State Transfer) is an architectural style used to design web APIs.

A REST API allows applications to communicate using HTTP methods.

Example:

Client → REST API → Database

---

# REST Principles

- Client and Server are separate.
- Every resource has a unique URL.
- Requests should be stateless.
- Standard HTTP methods are used.
- Responses are usually in JSON format.

---

# Example REST API

Get all users

GET /api/users

Get one user

GET /api/users/1

Create user

POST /api/users

Update user

PUT /api/users/1

Delete user

DELETE /api/users/1

---

# JSON

Most REST APIs exchange data using JSON.

Example:

```json
{
  "name": "Tanmay",
  "course": "BCA"
}
```

---

# Advantages of REST APIs

- Easy to understand
- Lightweight
- Platform independent
- Fast communication
- Widely used in modern web development
- Easy to test using Postman

---

# Summary

HTTP is the protocol used for communication between clients and servers. REST is a standard approach for building web APIs using HTTP methods such as GET, POST, PUT, PATCH, and DELETE. Together they form the foundation of modern web applications.
