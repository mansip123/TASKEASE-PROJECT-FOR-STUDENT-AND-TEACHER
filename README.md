# TaskEase 📋

**TaskEase** is a user-friendly and modular **web-based Task Management application** built using **PHP** and powered by a **MySQL database** for seamless CRUD operations. It simplifies task tracking and management for both **administrators** and **users**, ensuring improved productivity and workflow within an organization or academic environment.

---

## 🌟 Features

- 👥 **User Roles** – Two distinct roles: **Administrators** and **Regular Users**, each with specific access and privileges.
- ✅ **Task Assignment** – Admins can assign tasks directly to users.
- 📈 **Progress Tracking** – Users can update the status of their tasks.
- 📅 **Leave Management** – Users can apply for leave with date/type; admins can approve or reject requests.
- 🛠️ **PHP Backend** – Robust, secure server-side logic using PHP.
- 🗄️ **MySQL Database** – Securely stores user data, task info, and leave requests.
- 🎨 **Responsive Frontend** – Simple, clean UI using HTML, CSS, JavaScript, and Bootstrap.

---

## 🛠️ Technology Stack

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: PHP
- **Database**: MySQL
- **Others**: jQuery, phpMyAdmin (via XAMPP)

---

## 📂 Additional Files

- 📑 **Project Report**: `Report.pdf`
- 📽️ **Demo Video**: `Explainer Video`
- 🖼️ **Presentation**: `TaskEase.pdf`

---

## ⚙️ Installation Guide

To set up **TaskEase** on your local machine, follow these steps:

 1️⃣ Install Prerequisites
- [Download XAMPP](https://www.apachefriends.org/index.html) which includes Apache, PHP, and MySQL.

 2️⃣ Clone the Repository
Place the repo in your XAMPP `htdocs` folder:
```bash
cd C:/xampp/htdocs
git clone https://github.com/mansip123/TaskEase.git
3️⃣ Start Apache & MySQL
Open XAMPP Control Panel.
Start Apache and MySQL.

4️⃣ Create Database
Open phpMyAdmin at http://localhost/phpmyadmin

Create a new database (e.g., taskease_db)

Import the provided tms_db.sql file to set up required tables

5️⃣ Run the Project
In your browser, go to:

arduino
Copy
Edit
http://localhost/TaskEase
📁 Project Structure
pgsql
Copy
Edit
TaskEase/
├── css/
├── js/
├── includes/
├── templates/
├── tms_db.sql
├── Report.pdf
├── TaskEase.pdf
├── index.php
└── README.md
🤝 Contribution
Have suggestions or improvements? Fork the repo, make your changes, and submit a pull request.

bash
Copy
Edit
git pull origin main
# Make your changes
git push origin main
