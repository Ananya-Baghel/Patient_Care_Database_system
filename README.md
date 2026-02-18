# 🏥 Patient Care Database System

The **Patient Care Database System** is a web-based application developed using **PHP** and **MySQL** to manage patient-related information in a healthcare environment.  

This system helps hospitals, clinics, or medical institutions maintain patient records digitally, making data handling more efficient, organized, and secure.

---

## 📌 Project Overview

Managing patient information manually can be time-consuming and error-prone.  
This project provides a structured database-driven solution where patient details, medical records, and uploaded documents can be stored and accessed easily.

The system is designed for administrative and healthcare staff to improve patient data management.

---

## ✨ Features

- ✅ Patient registration and record management  
- ✅ Admin module for managing healthcare data  
- ✅ Secure storage of patient information in a database  
- ✅ Upload and maintain patient-related documents  
- ✅ User-friendly web interface  
- ✅ Organized folder structure for scalability  

---

## 🛠️ Technology Stack

| Component   | Technology Used |
|------------|----------------|
| Frontend   | HTML, CSS, JavaScript |
| Backend    | PHP |
| Database   | MySQL / MariaDB |
| Server     | Apache (XAMPP/WAMP recommended) |

---

## 📂 Project Structure

```plaintext
Patient_Care_Database_system
│
├── admin/               # Admin module files
├── classes/             # Classes and utilities
├── config/              # Configuration settings
├── database/            # Database connection and SQL files
├── dist/                # CSS, images, and other assets
├── js/                  # Client-side JavaScript files
├── uploads/             # Uploaded files directory
│
├── index.php            # Main entry page of the application
├── initialize.php       # Initialization logic and setup
├── config.php           # Main application configuration file
├── 404.html             # Custom error page
└── README.md            # Project documentation
```
---

## 🚀Installation & Setup

Follow these steps to run the project locally:

1️⃣ Clone the Repository

```git clone https://github.com/Ananya-Baghel/Patient\_Care\_Database\_system.git```

2️⃣ Move into the Project Folder

```cd Patient\_Care\_Database\_system```

3️⃣ Setup Local Server

```Install XAMPP or WAMP, then place the project folder inside:

XAMPP → htdocs/

WAMP → www/

Example:

C:\\xampp\\htdocs\\Patient\_Care\_Database\_system
```

4️⃣ Configure Database

Open phpMyAdmin

Create a new database:
```
CREATE DATABASE patient\_care;
```

Import the .sql file available inside the database/ folder.

5️⃣ Update Database Credentials

Edit the database settings inside config.php:

```
$host = "localhost";

$user = "root";

$password = "";

$database = "patient\_care";
```

6️⃣ Run the Project

Start Apache & MySQL from XAMPP/WAMP and open:

```
http://localhost/Patient\_Care\_Database\_system/
```
---

## 📌  Usage

- Open the application homepage (index.php)

- Admin users can manage patient records

- Upload documents and maintain medical history

- Access stored data through the database-driven interface

---

## 🔮Future Improvements

- Some enhancements that can be added:

- Role-based login system (Doctor, Nurse, Admin)

- Appointment scheduling module

- Better UI using Bootstrap or React

- API integration for mobile healthcare apps

- Improved security features

---

## 🤝 Contributing

Contributions are welcome!

Fork the repository

Create a new branch

Commit changes

Submit a Pull Request

---

## 📄 License

This project is open-source and available for educational purposes.

---

## 👩‍💻 Author

Ananya Baghel

GitHub: Ananya-Baghel
