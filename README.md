## EduManager - Student Management App
Welcome to EduManager, a full-stack application designed to manage students and their courses efficiently. This app allows administrators to add, edit, and delete students, assign them to courses, and track key metrics via a dashboard.

### Table of Contents
Features
Technologies Used
Screenshots
Installation
Usage
Contributing
License

### Features

Add new students with their full name, email, and course assignment.
View and manage a list of all students with details like ID, name, course, enrollment date, and status.
Edit or delete existing student records.
Manage courses, including adding new courses with name, description, duration, and status.
Dashboard overview to track:
Total number of students.
Number of active courses.
Number of graduates.
Success rate percentage.


Search functionality to find students quickly.

### Technologies Used

Frontend: HTML, CSS, JavaScript (React.js implied from the UI structure)
Backend: Node.js, Express.js
Database: MongoDB
Dependencies:
winston - For logging
morgan - For HTTP request logging
cors - For enabling cross-origin resource sharing
nodemon - For automatic server restarts during development
dotenv - For managing environment variables



### Screenshots
All Students View
https://i.imgur.com/IsKYwPe.png for the "All Students View".
https://i.imgur.com/3n2WCze.png for the "Dashboard View".
https://i.imgur.com/238g5l3.png for the "Add New Student Modal".
https://i.imgur.com/w2ztYZL.png for the "Course Management View

## Clone the repository:
git clone https://github.com/your-username/edumanager.git
cd edumanager


### Install dependencies:

For the backend:npm install
Ensure you have MongoDB installed and running locally or update the connection string in your .env file.


### Set up environment variables:

Create a .env file in the root directory.
Add the following variables (replace with your actual values):PORT=3000
MONGODB_URI=mongodb://localhost:27017/edumanager
NODE_ENV=development




### Start the application:
node server.js


### Usage

Navigate to the Dashboard to view an overview of students and courses.
Go to Students to manage student records, including adding new students via the + Add Student button.
Visit Courses to manage course details, including adding new courses with the + Add Course button.
Use the search bar to filter students by name or other criteria.
Click Edit or Delete buttons to modify or remove records.

### Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -m "Add new feature").
Push to the branch (git push origin feature-branch).
Open a pull request.

### License
### This project is licensed under the MIT License. See the LICENSE file for details.
