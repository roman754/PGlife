# PG Life — Hostel/PG Listing Website

PG Life is a simple web application that allows users to browse and shortlist PG/hostel accommodations across major Indian cities. It includes user signup/login, listing pages, property details, and a dashboard for interested properties.

## 🚀 Features

- User authentication (Signup/Login/Logout)
- Browse PG listings with filters
- View property details with images and features
- Mark properties as “Interested”
- Dashboard to view shortlisted properties

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, Bootstrap, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Other Tools**: XAMPP or LAMP for local hosting

## 📁 Project Structure

PGlife/
├── index.php # Home page
├── dashboard.php # User dashboard
├── property_list.php # List of all PGs
├── property_detail.php # Single property detail view
├── logout.php
├── api/ # AJAX and backend handlers
│ ├── login_submit.php
│ ├── signup_submit.php
│ └── toggle_interested.php
├── css/ # Stylesheets
├── img/ # Images for the website
└── LICENSE


## 🧑‍💻 How to Run Locally

1. **Install XAMPP** (or LAMP/MAMP/WAMP depending on your OS).
2. **Clone or extract this project** into `htdocs` (XAMPP) folder.
3. **Create a MySQL database** named `pglife`.
4. **Import the database** using `pglife.sql` (make sure it's available).
5. Start **Apache and MySQL** via XAMPP.
6. Visit: `http://localhost/PGlife/index.php`

## 🔐 Important Notes

- Ensure database credentials in the PHP files (`config.php` if exists) are correctly set.
- Foreign key constraints are used. To avoid deletion errors, handle related rows carefully or use `ON DELETE CASCADE`.

## 📄 License

This project is licensed under the MIT License.
