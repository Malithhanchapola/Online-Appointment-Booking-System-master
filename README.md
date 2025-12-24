# Appointment Booking System

## Overview

The **Appointment Booking System** is a web-based platform designed for **retail chain clinics** to simplify and modernize the appointment scheduling process. It allows patients to book, view, and manage appointments online while enabling clinic managers and administrators to efficiently control doctors, clinics, and appointment workflows through dedicated dashboards.

This system eliminates long queues and manual scheduling by providing a **centralized, user-friendly online solution** for patients, medical staff, and clinic administrators.

## Features

### Patient Features

* User registration and secure login
* Book appointments online
* Cancel existing appointments
* View appointment status
* Check doctor availability
* Search clinics and doctors

### Manager Features

* View all appointments for assigned clinics
* Update appointment statuses
* Monitor patient bookings

### Admin Features

* Add and remove doctors, clinics, and managers
* View all registered doctors, clinics, and managers
* Assign doctors to clinics
* Assign managers to clinics

## Technologies Used

* **Frontend:** HTML5, CSS3, JavaScript, jQuery
* **Backend:** PHP
* **Database:** MySQL
* **Asynchronous Communication:** AJAX
* **Version Control:** Git & GitHub

## System Requirements

* PHP server (XAMPP / WAMP)
* MySQL Database
* Web browser with HTML5 support
  *(Google Chrome recommended)*

## Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/AppointmentBookingSystem.git
   ```
2. Move the project folder to your XAMPP/WAMP `htdocs` directory.
3. Import the database:

   * Open **phpMyAdmin**
   * Import the `wt_database.sql` file
   * Default credentials:

     * Username: `root`
     * Password: *(empty)*
4. Configure database connection:

   * Update credentials in `dbconfig.php` if needed.
5. Start Apache and MySQL services.
6. Open the application in your browser:

   ```text
   http://localhost/AppointmentBookingSystem/cover.php
   ```

## Usage

* Patients can register and book appointments directly from the home page.
* Admin and Manager logins are available on the same login page.
* Logout redirects users to the main landing page.

### Test Login Credentials

| Role    | Username | Password |
| ------- | -------- | -------- |
| Admin   | admin    | admin    |
| Manager | manager  | manager  |
| Patient | user     | user     |

## Contributing

Contributions are welcome to improve this system.

1. Fork the repository
2. Create a new branch:

   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:

   ```bash
   git commit -m "Add new feature"
   ```
4. Push to GitHub:

   ```bash
   git push origin feature-branch
   ```
5. Open a pull request

## Contact

For feedback, suggestions, or collaboration:

* **Email:** malithhanchapola1@gmail.com
* **GitHub:** https://github.com/Malithhanchapola
