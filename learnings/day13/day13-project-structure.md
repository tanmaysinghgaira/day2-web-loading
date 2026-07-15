# Day 13 - Project Structure for Backend

The backend project structure for the Resume Builder application:

```
resumeflow-backend/
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

## Folder Organization

- **server.js**: Main entry point for the Express application
- **package.json**: Project dependencies and metadata
- **routes/**: Contains all API route handlers organized by resource

Each route file handles all HTTP methods (GET, POST, PUT, DELETE) for that specific resource.
