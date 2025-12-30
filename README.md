Course Scheduling Project
Overview

The Course Scheduling Project is a web application designed to help students at Qassim University efficiently organize and schedule the courses they want to register for each semester. The system allows students to prioritize and arrange their desired courses based on their preferences, academic requirements, and available course slots. By providing a simple, user-friendly interface, this project helps students create an optimal course schedule for each semester.

Developed during an internship at Deanship of Information Technology – Qassim University (QUIT), this project aims to enhance students' academic experience by simplifying the course registration process and providing a better organizational tool for managing course schedules.

Project Goals

Streamline the process of course registration for students.

Allow students to prioritize and arrange their desired courses based on available slots and personal preferences.

Provide an easy-to-use, interactive dashboard for students to visualize and manage their course schedule.

Implement a backend system to efficiently manage course data and registration details.

Frontend Design

Below are images showcasing the frontend design of the project:

Frontend design 1

<img width="2880" height="1920" alt="Frontend design" src="https://github.com/user-attachments/assets/8ea5d2d3-6c00-4dab-a39f-61fbdf2947cd" />


Frontend design 2

<img width="968" height="419" alt="Frontend design 2" src="https://github.com/user-attachments/assets/2194ca0c-e7e4-4e62-a56a-2c57a65c989c" />

Team Members

This project was developed as part of a team of 5 students during our internship at Deanship of Information Technology – Qassim University (QUIT).

Key Features

Course Scheduling: Students can create their optimal course schedule based on personal preferences and available course slots.

Full-Stack Web Application: Built with Laravel for backend development and MySQL for database management. The frontend is developed using HTML, CSS, and JavaScript.

Interactive Dashboard: An easy-to-use dashboard where students can view and manage their course schedule.

User-Friendly Interface: The system provides an intuitive interface for students to select, prioritize, and organize their courses.

Backend System: Manages course data, student registrations, and course availability.

Technologies Used

Backend: Laravel, PHP

Frontend: HTML, CSS, JavaScript

Database: MySQL

Version Control: Git, GitHub (Git Flow methodology)

Project Setup

To set up and run the project locally, follow these steps:

1. Clone the repository
git clone https://github.com/yasir239/Intership.git

2. Navigate to the project directory
cd Intership

3. Install the required dependencies
composer install

4. Set up the environment variables

Copy .env.example to .env:

cp .env.example .env

5. Generate the application key
php artisan key:generate

6. Run database migrations
php artisan migrate

7. Serve the application
php artisan serve
