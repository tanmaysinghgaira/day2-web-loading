# Day 14 – Backend Practical & API Testing

## Objective

The objective of today's session was to complete the backend API development, test all API endpoints using Postman, fix any remaining issues, and finalize the project.

---

# What is Postman?

Postman is an API testing tool that allows developers to send HTTP requests to a server and view the responses without creating a frontend application.

It is commonly used to test REST APIs during backend development.

---

# Why Do We Use Postman?

- Test APIs quickly
- Verify API responses
- Debug backend applications
- Check status codes
- Send request bodies and headers
- Save API collections for future testing

---

# Installing Postman

1. Download Postman from the official website.
2. Install the application.
3. Open Postman.
4. Create a new request.

---

# Starting the Server

Run the backend server:

```bash
node server.js
```

If successful, the terminal displays:

```text
Server running on port 3000
```

---

# Base URL

```
http://localhost:3000
```

---

# Testing Authentication APIs

## Register User

Method:

```
POST
```

Endpoint:

```
/api/auth/register
```

---

## Login User

Method:

```
POST
```

Endpoint:

```
/api/auth/login
```

---

## Logout User

Method:

```
POST
```

Endpoint:

```
/api/auth/logout
```

---

# Testing Resume APIs

Create Resume

```
POST /api/resumes
```

Get All Resumes

```
GET /api/resumes
```

Get Resume by ID

```
GET /api/resumes/:id
```

Update Resume

```
PUT /api/resumes/:id
```

Delete Resume

```
DELETE /api/resumes/:id
```

---

# Testing Profile API

```
GET /api/profile
```

```
PUT /api/profile
```

---

# Testing Other Resources

- Education
- Experience
- Skills
- Projects
- Applications

Each API should return the expected JSON response without errors.

---

# HTTP Status Codes

200 – Success

201 – Resource Created

400 – Bad Request

401 – Unauthorized

404 – Not Found

500 – Internal Server Error

---

# Common Problems

## Server Not Starting

Possible reasons:

- Express is not installed.
- Wrong file name.
- Syntax error.
- Incorrect port.

---

## Route Not Found

Possible reasons:

- Incorrect endpoint.
- Wrong HTTP method.
- Route not imported into `server.js`.

---

## JSON Error

Possible reason:

Missing middleware:

```javascript
app.use(express.json());
```

---

# Final Checklist

- Express installed
- Server running successfully
- All routes created
- APIs tested in Postman
- Correct HTTP methods used
- JSON responses returned
- No syntax errors
- Code pushed to GitHub

---

# Learning Outcome

Today I completed the backend practical by testing APIs with Postman and verifying that every endpoint worked correctly. I learned how to identify and fix API errors, understand HTTP responses, and ensure that the backend is ready for frontend integration.
