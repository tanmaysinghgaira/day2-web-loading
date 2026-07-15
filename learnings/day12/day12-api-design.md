# AI Resume Builder - API Design

## What is a Resource?

A resource is any object or data that an API manages.

Examples:
- User
- Resume
- Education
- Experience
- Skills
- Projects
- Applications

---

# Resource 1: Authentication

## Register User

Method: POST

Endpoint:

POST /api/auth/register

Description:

Creates a new user account.

---

## Login User

Method: POST

Endpoint:

POST /api/auth/login

Description:

Authenticates an existing user.

---

## Logout User

Method: POST

Endpoint:

POST /api/auth/logout

Description:

Logs out the current user.

---

# Resource 2: User Profile

## Get Profile

GET /api/profile

Returns logged-in user's profile.

---

## Update Profile

PUT /api/profile

Updates profile information.

---

# Resource 3: Resume

## Create Resume

POST /api/resumes

Creates a new resume.

---

## Get All Resumes

GET /api/resumes

Returns all resumes of the logged-in user.

---

## Get Resume by ID

GET /api/resumes/:id

Returns one resume.

---

## Update Resume

PUT /api/resumes/:id

Updates a resume.

---

## Delete Resume

DELETE /api/resumes/:id

Deletes a resume.

---

# Resource 4: Education

POST /api/resumes/:id/education

Add education.

GET /api/resumes/:id/education

View education.

PUT /api/resumes/:id/education/:educationId

Update education.

DELETE /api/resumes/:id/education/:educationId

Delete education.

---

# Resource 5: Experience

POST /api/resumes/:id/experience

GET /api/resumes/:id/experience

PUT /api/resumes/:id/experience/:experienceId

DELETE /api/resumes/:id/experience/:experienceId

---

# Resource 6: Skills

POST /api/resumes/:id/skills

GET /api/resumes/:id/skills

PUT /api/resumes/:id/skills/:skillId

DELETE /api/resumes/:id/skills/:skillId

---

# Resource 7: Projects

POST /api/resumes/:id/projects

GET /api/resumes/:id/projects

PUT /api/resumes/:id/projects/:projectId

DELETE /api/resumes/:id/projects/:projectId

---

# Resource 8: Applications

POST /api/applications

Create a job application.

GET /api/applications

Get all applications.

GET /api/applications/:id

Get one application.

PUT /api/applications/:id

Update application.

DELETE /api/applications/:id

Delete application.

---

# HTTP Methods Used

GET → Read data

POST → Create new data

PUT → Update complete resource

PATCH → Update selected fields

DELETE → Remove data

---

# Summary

This API design identifies the main resources required for the AI Resume Builder application. Each resource has clear RESTful endpoints and appropriate HTTP methods. This design serves as the blueprint for backend development.
