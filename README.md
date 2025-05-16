# Clinic Booking System

## 🏥 Project Title
Clinic Booking System - A Relational Database for Managing Healthcare Appointments

## 📄 Description

**The Clinic Booking System** is a relational database project designed to manage patients, doctors, appointments, treatments, and payments in a healthcare clinic. This system streamlines clinic operations by enabling efficient booking, record tracking, and payment handling.

### 💡 Key Features
- Manage patient and doctor records
- Book and track appointments
- Link multiple treatments to appointments
- Record and monitor payments
- Enforce data consistency with constraints and foreign keys

## 🚀 How to Run / Setup the Project

### 1. **Install MySQL Workbench and MySQL Server**
- Download and install MySQL Workbench: [https://dev.mysql.com/downloads/workbench/](https://dev.mysql.com/downloads/workbench/)

### 2. **Connect to MySQL Server**
- Open MySQL Workbench
- Click on `+` to add a new MySQL connection
- Provide a connection name, hostname (`localhost`), port (`3306`), and username (`root`)
- Test connection and save

### 3. **Import SQL File**
- Click your connection to open it
- From the toolbar, choose **File > Open SQL Script...**
- Select the provided SQL file containing your `clinicbooking` database
- Execute the script using the lightning bolt button (⚡) or `Ctrl + Shift + Enter`

### 4. **Explore the Database**
- Use `USE clinicbooking;` to select the database
- Run `SELECT` statements to view data in tables like:
  ```sql
  SELECT * FROM patients;
  SELECT * FROM appointments;
