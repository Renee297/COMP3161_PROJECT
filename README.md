# COMP3161_PROJECT
# COMP3161 Final Project – Course Management System

## Project Overview

This project is a course management system based on the OURVLE platform. 

The system provides a database and REST API that allows students, lecturers, and administrators to manage courses, assignments, forums, and course content.

---

## Features

### User Management
- Register new users
- Login for students, lecturers, and admins
- Role-based access control

### Course Management
- Create courses (admin only)
- Retrieve all courses
- Retrieve courses for a student
- Retrieve courses for a lecturer
- Register students for courses
- Retrieve course members

### Calendar
- Create calendar events
- Retrieve events for a course
- Retrieve events for a student by date

### Forums
- Create forums
- Retrieve forums by course
- Create discussion threads
- Add replies to threads
- Nested replies supported

### Course Content
- Add course materials
- Organize content by sections/modules
- Retrieve course content

### Assignments
- Create assignments
- Submit assignments
- Grade submissions
- Calculate student averages

### Reports (Views)
- Courses with 50 or more students
- Students taking 5 or more courses
- Lecturers teaching 3 or more courses
- Top 10 most enrolled courses
- Top 10 students by overall average

---

## Technologies Used

- Python
- MySQL
- Flask
- SQL
- Postman

---

## Database Requirements

The database was populated according to the project specifications:

- 100,000 students
- 50 lecturers
- 1 admin
- 200 courses
- Students enrolled in 3–6 courses
- Each course has at least 10 students
- Each lecturer teaches 1–5 courses

---
