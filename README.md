# **Assignment: Full-Stack CRUD Application Development with DevOps Practices**

## Basic Info

* **Practices Topic: News Management System-Admin**
* **Student Name: Gaobo Wu**
* **Student No: n11942487**

## Submission Items

* **JIRA Project Board URL: [News Management System-Admin](https://bluewu129.atlassian.net/jira/software/projects/NMSA/summary)**
* **Requirement diagram: ![](https://github.com/Bluewu129/sdlapps/blob/main/doc/NEWS_MIS_SysML.png)**

## Tech Stack
### Frontend
- React.js

### Backend
- Node.js with Express framework
- MongoDB for database storage
- JWT authentication

### DevOps
- GitHub Actions for CI/CD pipeline
- AWS EC2 for deployment（QUT Student account）

## Project Structure
```
sdlapps/
├── .github/          # GitHub Actions workflows
├── backend/          # Backend Node.js application
│   ├── config/       # Mongodb config
│   ├── controllers/  # Request handlers
│   ├── models/       # Database models
│   ├── routes/       # API routes
│   └── middleware/   # Custom middleware
├── frontend/         # React frontend application
│   ├── public/       # Static files
│   ├── src/          # React components
│   └── package.json  # Frontend dependencies
└── doc               # SysML diagram
└── README.md         # Project documentation
```

## CI/CD Pipeline
This project uses GitHub Actions for continuous integration and deployment. The workflow includes:

1. Automated testing of backend and frontend code
2. Building and packaging of the application
3. Deployment to AWS EC2 instance