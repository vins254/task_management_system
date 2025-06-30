# Web-Based Task Management System

This project is a role-based task management system built using PHP, MySQL, JavaScript, HTML, CSS, and Bootstrap. It supports three roles: Administrator, Project Manager, and Employee, allowing for task creation, assignment, tracking, and reporting within projects.

#Features

- User Authentication (Login)
- Role-based Access Control
- Create/View/Edit/Delete Projects and Tasks
- Progress Tracking & Percentage Completion
- Task Status Monitoring
- Printable Reports
- Responsive UI with Bootstrap

#Technologies & Tools Used

- Frontend: HTML, CSS, JavaScript, Bootstrap
- Backend: PHP (Core PHP)
- Database: MySQL
- Web Server: Apache (via XAMPP/WAMP/LAMP)
- Version Control: Git (optional)
- VS Code / Sublime Text / PHPStorm (for development)
- phpMyAdmin (for database management)


#System Requirements

- Operating System: Windows / Linux / macOS
- PHP: Version 7.4 or later
- MySQL: Version 5.7 or later
- Apache: Included in XAMPP/WAMP
- Browser: Chrome / Firefox / Edge

---

#Installation Guide

1)	Download and install [XAMPP](https://www.apachefriends.org/) (includes Apache, PHP, MySQL).
2)	Start Apache and MySQL from the XAMPP Control Panel.
3)	Clone or download the project folder.
4)	Paste the project folder into `htdocs` directory of XAMPP:  C:\xampp\htdocs\task-management-system\

5)	Open **phpMyAdmin**: http://localhost/phpmyadmin
6)	Create a new database: tms.db
7)	Import the SQL file:
- Navigate to `Import` tab
- Upload and import “tms.db” from the project directory

8)	Open “db_connect.php” in the project.
9)	Update your credentials: 
$conn= new mysqli('localhost', 'root', '', 'tms_db')

10)	Open your browser and visit: http://localhost/task_management_system/  to run application

Default login details

admin@gmail.com
admin123

		
		



