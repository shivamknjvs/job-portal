# JobPortal

A full-stack JobPortal web application built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js) that enables job seekers to search and apply for jobs while allowing employers to post job listings and manage applicants.

## Live Demo

[Click here to view the live application](https://job-portal-one-ebon.vercel.app/)

## Features

- **User Authentication**: Role-based authentication for job seekers and employers using JWT tokens.
- **Job Search**: Search for jobs with filters such as category, location, and experience level.
- **Job Application**: Job seekers can apply to jobs, save jobs, and view application status.
- **Job Posting**: Employers can create, update, and manage job listings.
- **Profile Management**: Separate dashboards for job seekers and employers to manage their profiles, applications, and job postings.
- **Responsive Design**: Fully responsive, providing a seamless experience on all devices.

## Technologies Used

- **Frontend**: 
  - React.js
  - Material-UI for UI components
  - Redux for state management
- **Backend**: 
  - Node.js
  - Express.js
  - JWT (JSON Web Tokens) for authentication
- **Database**: 
  - MongoDB for storing job listings, user data, and applications
- **Deployment**: 
  - Deployed using Render

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/shivamknjvs/JobPortal.git
   cd JobPortal

2. Install dependencies for both the frontend and backend:
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
3. Create a .env file in the backend folder and add the following environment variables:
MONGO_URI=your-mongodb-uri
JWT_SECRET=your-secret-key
4. Run the application:
# Backend
cd backend
npm start

# Frontend
cd ../frontend
npm start
