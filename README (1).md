# Job Portal

## Overview
This is a full-stack job portal application with role-based access control (Admin, Company, Job Seeker). It allows users to post jobs, manage applications, and upload resumes.

## Features
- **Role-Based Access Control**: Different UI and access for Admin, Companies, and Job Seekers.
- **File Uploads**: Job Seekers can upload resumes.
- **Company Dashboard**: Companies can manage job postings.
- **Optimized Database Queries**: Uses Prisma/Sequelize for database operations.

## Installation

### Backend
1. Navigate to the backend directory:
   ```sh
   cd backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the server:
   ```sh
   npm start
   ```

### Frontend
1. Navigate to the frontend directory:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the frontend server:
   ```sh
   npm start
   ```

## API Endpoints
- `POST /api/jobs` - Create a job posting (Company only)
- `GET /api/jobs` - Retrieve job postings
- `DELETE /api/jobs/:id` - Delete a job posting (Company only)
- `POST /api/resume` - Upload a resume (Job Seeker only)

## Technologies Used
- **Frontend**: React, Bootstrap
- **Backend**: Node.js, Express, Prisma/Sequelize
- **Database**: PostgreSQL/MySQL

## License
This project is licensed under the MIT License.
