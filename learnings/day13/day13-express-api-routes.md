# Day 13 - Full Web Flow & Express

## Objective

The goal of today's task is to create API routes for the AI Resume Builder project using Express.js.

An API route is a URL that allows the frontend to communicate with the backend. Every route performs a specific task such as creating a user, logging in, creating a resume, or deleting a project.

---

# What is Express?

Express.js is a lightweight framework built on Node.js. It helps developers build web servers and APIs quickly with less code.

---

# Project Structure

```
ResumeFlow/
│
├── server.js
├── package.json
│
├── routes/
│   ├── auth.js
│   ├── profile.js
│   ├── resumes.js
│   ├── education.js
│   ├── experience.js
│   ├── skills.js
│   ├── projects.js
│   └── applications.js
```

---

# Resources

The main resources in the Resume Builder project are:

- Authentication
- User Profile
- Resume
- Education
- Experience
- Skills
- Projects
- Applications

Each resource has its own API routes.

---

# Authentication Routes

| Method | Endpoint | Purpose |
|---------|----------|----------|
| POST | /api/auth/register | Register a new user |
| POST | /api/auth/login | Login user |
| POST | /api/auth/logout | Logout user |

---

# Profile Routes

| Method | Endpoint | Purpose |
|---------|----------|----------|
| GET | /api/profile | Get user profile |
| PUT | /api/profile | Update profile |

---

# Resume Routes

| Method | Endpoint | Purpose |
|---------|----------|----------|
| POST | /api/resumes | Create resume |
| GET | /api/resumes | Get all resumes |
| GET | /api/resumes/:id | Get one resume |
| PUT | /api/resumes/:id | Update resume |
| DELETE | /api/resumes/:id | Delete resume |

---

# Education Routes

| Method | Endpoint |
|---------|----------|
| POST | /api/education |
| GET | /api/education |
| PUT | /api/education/:id |
| DELETE | /api/education/:id |

---

# Experience Routes

| Method | Endpoint |
|---------|----------|
| POST | /api/experience |
| GET | /api/experience |
| PUT | /api/experience/:id |
| DELETE | /api/experience/:id |

---

# Skills Routes

| Method | Endpoint |
|---------|----------|
| POST | /api/skills |
| GET | /api/skills |
| PUT | /api/skills/:id |
| DELETE | /api/skills/:id |

---

# Projects Routes

| Method | Endpoint |
|---------|----------|
| POST | /api/projects |
| GET | /api/projects |
| PUT | /api/projects/:id |
| DELETE | /api/projects/:id |

---

# Applications Routes

| Method | Endpoint |
|---------|----------|
| POST | /api/applications |
| GET | /api/applications |
| GET | /api/applications/:id |
| PUT | /api/applications/:id |
| DELETE | /api/applications/:id |

---

# HTTP Methods

GET – Read data

POST – Create new data

PUT – Update existing data

DELETE – Remove data

---

# Testing

After creating all routes:

1. Start the server using `node server.js`.
2. Open Postman.
3. Test every endpoint.
4. Verify that each route returns a JSON response.

---

# Learning Outcome

After completing this task, I understood how Express.js is used to create API routes. I learned how different HTTP methods work, how routes are organized into separate files, and how the frontend communicates with the backend through these routes.
