# Day 11 – HTTP Standards & REST APIs

## Introduction

Today I learned about HTTP, REST APIs, HTTP methods, status codes, and how the frontend communicates with the backend using APIs. These concepts are the foundation of modern web development.

---

# What is HTTP?

HTTP (HyperText Transfer Protocol) is a communication protocol that allows a client (browser or mobile app) to exchange data with a server over the internet.

Example:

Browser → HTTP Request → Server

Server → HTTP Response → Browser

---

# Client and Server

## Client

A client is an application that requests data.

Examples:
- Web Browser
- Mobile App
- Desktop Application

## Server

A server receives requests, processes them, and sends responses back to the client.

---

# What is an API?

API stands for **Application Programming Interface**.

It acts like a messenger between the frontend and the backend.

Example:

User clicks **Login**

↓

Frontend sends request

↓

API receives the request

↓

Backend processes it

↓

API sends the response back to the frontend

---

# What is REST API?

REST (Representational State Transfer) is a standard way of building APIs.

REST APIs use HTTP methods to perform operations on resources.

Example:

```
GET /users
POST /users
PUT /users/1
DELETE /users/1
```

---

# HTTP Methods

## GET

Used to retrieve data.

Example:

```
GET /api/users
```

---

## POST

Used to create new data.

Example:

```
POST /api/users
```

---

## PUT

Used to update an existing resource completely.

Example:

```
PUT /api/users/1
```

---

## PATCH

Used to update only selected fields of a resource.

Example:

```
PATCH /api/users/1
```

---

## DELETE

Used to remove data.

Example:

```
DELETE /api/users/1
```

---

# HTTP Status Codes

## 200 OK

The request was successful.

## 201 Created

A new resource was created successfully.

## 400 Bad Request

The request sent by the client is invalid.

## 401 Unauthorized

Authentication is required.

## 403 Forbidden

The client does not have permission.

## 404 Not Found

The requested resource does not exist.

## 500 Internal Server Error

Something went wrong on the server.

---

# Request and Response

## HTTP Request

A request contains:

- Method
- URL
- Headers
- Body (optional)

Example:

```
POST /api/login
```

---

## HTTP Response

A response contains:

- Status Code
- Headers
- Response Body

Example:

```json
{
  "message": "Login Successful"
}
```

---

# JSON

Most APIs use JSON (JavaScript Object Notation) to exchange data.

Example:

```json
{
  "name": "Tanmay",
  "course": "BCA",
  "city": "Haldwani"
}
```

---

# Advantages of REST APIs

- Easy to understand
- Fast communication
- Platform independent
- Lightweight
- Uses standard HTTP methods
- Easy to test with Postman

---

# Learning Outcome

Today I learned how HTTP allows communication between clients and servers. I understood the purpose of REST APIs, HTTP methods, status codes, requests, responses, and JSON. These concepts are essential for building backend applications using Node.js and Express.js.
