# 🎓 Campus Recruitment Management System (CRMS)

A full-featured web-based Campus Recruitment Management System designed to streamline the recruitment process for **students**, **companies**, and **administrators**.

---

## 🌐 Live Preview

> Local Project (PHP + MySQL) — Hosted via XAMPP  
> To run the project: open in browser as `http://localhost/crms`

---

## 🖼️ Screenshots

| 🔹 Home Page | 🔹 Student Dashboard |
|-------------|----------------------|
| ![Home Page](https://github.com/user-attachments/assets/13789a41-c5ec-4593-ad0c-556cf049a842) | ![Student Dashboard](https://github.com/user-attachments/assets/b65993b8-61cb-4865-9b5f-f1eb76f814d3) |

| 🔹 Company Dashboard | 🔹 Admin Dashboard |
|----------------------|-------------------|
| ![Company Dashboard](https://github.com/user-attachments/assets/3b286f52-4a07-42f7-9d80-2da250d219b1) | ![Admin Dashboard](https://github.com/user-attachments/assets/bf7c8cef-e6d2-46b5-a25e-56d5271a2c5e) |


---

## 🔐 Login Credentials

| Role      | Username / Email             | Password   |
|-----------|------------------------------|------------|
| **Admin**     | `admin`                        | `admin123` |
| **Candidate** | `gr3327@srmist.edu.in`         | `pass123`  |
| **Employer**  | `gr3327@srmist.edu.in`         | `pass123`  |

---

## 🛠️ Features

### 🧑‍🎓 Student (Candidate) Panel:
- View listed jobs
- Apply to jobs
- Fill education profile
- Track application history
- View reports and stats

### 🧑‍💼 Employer Panel:
- Post new vacancies
- View and manage job applications
- Shortlist / Accept / Reject candidates
- Generate reports

### 🛡️ Admin Panel:
- View total registered users and companies
- Manage jobs and applications
- Monitor platform activity

---

## ⚙️ Tech Stack

- 💻 Frontend: HTML, CSS, Bootstrap
- 🧠 Backend: PHP
- 🗄️ Database: MySQL
- 📦 Server: XAMPP / Apache

---

## 📁 Folder Structure

```plaintext
crms/
├── admin/
│   ├── dashboard.php
│   ├── manage_companies.php
│   ├── manage_users.php
│   ├── reports.php
│   └── ...
│
├── candidate/
│   ├── dashboard.php
│   ├── apply_job.php
│   ├── education_form.php
│   ├── history.php
│   └── ...
│
├── company/
│   ├── dashboard.php
│   ├── post_vacancy.php
│   ├── view_applications.php
│   ├── reports.php
│   └── ...
│
├── includes/
│   ├── db.php                # Database connection file
│   ├── header.php            # Common header
│   ├── footer.php            # Common footer
│   └── functions.php         # Utility functions
│
├── assets/
│   ├── css/
│   ├── js/
│   ├── images/
│   └── ...
│
├── uploads/                  # Uploaded resumes, company logos, etc.
├── config/
│   └── config.php            # Configuration and constants
├── database/
│   └── crms.sql              # SQL file to import the database
│
├── index.php                 # Landing/Home page
├── login.php                 # Sign In
├── register.php              # Registration form
├── logout.php                # Logout and end session
├── contact.php
├── about.php
├── listed_jobs.php
└── README.md

````

## 🚀 How to Run This Project

1. **Clone the repository:**
````bash
   git clone https://github.com/guvvalavenkat/campus-recruitment-system.git
````

2. **Move the project to XAMPP directory:**

````
   C:\xampp\htdocs\crms
````

3. **Start Apache and MySQL** using XAMPP Control Panel
````
4. **Import the database:**
````
   * Go to `http://localhost/phpmyadmin`
   * Create a database (e.g., `crms_db`)
   * Import the `.sql` file if provided (check `database/` or project root)
````
5. **Run the project in browser:**
````
   http://localhost/crms/
````

## 👤 Author
**Guvvala Venkat Reddy**
📧 Email: [guvvalavenkat4@gmail.com](mailto:guvvalavenkat4@gmail.com)

````

## 📄 License

This project is for academic and demonstration purposes only.



