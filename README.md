# Hospital Management System

A comprehensive management platform for healthcare facilities, featuring patient record tracking, doctor scheduling, and billing automation. This web-based application is designed to streamline hospital operations by providing distinct interfaces for administrators, doctors, and patients.

## 🚀 Features
* **Admin Dashboard:** Comprehensive control over doctor records, patient lists, and appointment oversight (`admin-panel.php`, `admin-panel1.php`).
* **Doctor Management:** Specialized tools for doctors to manage schedules and search for patients (`doctor-panel.php`, `doctorsearch.php`).
* **Patient Search & Tracking:** Efficient search functionality for both patient and doctor databases (`patientsearch.php`, `doctorsearch.php`).
* **Prescription & Reports:** Integrated system for issuing and managing medical prescriptions (`prescribe.php`).
* **Document Generation:** Automated PDF generation for reports and invoices using the **TCPDF** library.
* **Responsive Frontend:** Built with custom CSS and enhanced with **Font-Awesome** iconography (`style1.css`, `style2.css`, `font-awesome/`).

## 🛠️ Tech Stack
* **Backend:** PHP
* **Database:** MySQL / MariaDB
* **Dependencies:** Composer (Dependency Manager), TCPDF (PDF Generation)
* **Frontend:** HTML5, CSS3, JavaScript, Font-Awesome

## 📂 Project Structure
* `myhmsdb.sql`: The primary SQL file to initialize the database schema.
* `func.php`: Contains core backend logic and helper functions for database communication.
* `vendor/`: Directory containing PHP dependencies installed via Composer.
* `assets/` & `css/`: Core design and layout files.

## ⚙️ Installation Guide

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/hospital-management-system.git](https://github.com/YOUR_USERNAME/hospital-management-system.git)
