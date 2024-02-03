
<div align="center">
  <h1>ExamPor</h1>
  <p>
    A Online Exam portal website with backend in Nodejs and frontend in React js 

  Features:-
Student User
    View Tests Details
    Register for test
    Give Test
    Check Result and correct answer and explanation for questions
Teacher User
    Create, Update Questions and Question Banks
    Create, View Test
Admin User
    Create and Manage Teacher users
    Create and Manage subjects.


Tech Stack:-
    Frontend:-
                    React.js
                    React-Redux
                    Material UI library
                    HTML 5
                    CSS 3
    Backend:-
                    Node.js
                    Express.js
                    Passport.js
    Database:-
                    MongoDB
      </p>
  
How to run :-

Go to the project directory

```bash
  cd project-directory
```

Install dependencies

```bash
  cd backend
  npm install
  cd ../frontend
  npm install
  cd ../user-portal-frontend
  npm install
```

Start the backend server

```bash
  cd backend
  npm start
```

Start the frontend client for admin

```bash
  cd frontend
  npm start
```

Start the frontend client for teacher/student

```bash
  cd user-portal-frontend
  npm start
```

<b>Note</b> : admin user is created when backend runs first time. default admin (username, password) details are <b>("sysadmin","systemadmin"). addAdminIfNotFound() function of backend/services/admin.js file </b> is for this logic. You can check/modify default admin details from this function.

<!-- Run with Docker -->
### Run With Docker

build docker images

```bash
  docker-compose build
```

Run container and services

```bash
  docker-compose up
```



