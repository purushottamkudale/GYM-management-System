# Gym Management System

A web-based Gym Management System built with **PHP** and **MySQL**, designed to handle gym operations and membership management through separate admin and employer/user login flows with database-backed authentication.

## ✨ Features

- Admin dashboard for managing gym operations
- Employer/user registration and login
- Membership management backed by a MySQL database
- Role-based access (Admin vs. Employer/User)

## 🛠️ Tech Stack

- **PHP** — server-side logic
- **MySQL** — database
- **JavaScript** — client-side interactivity
- **CSS** — styling

## 📸 Screenshots

*(Add a screenshot of the admin dashboard and login page here — this is the easiest way to make the project instantly understandable to anyone browsing your GitHub.)*

## 🚀 Getting Started

### Prerequisites

- A local server environment: **XAMPP**, **WAMP**, or **LAMP**
- PHP and MySQL (bundled with the above)
- phpMyAdmin (also bundled)

### Installation

1. **Download and extract** this repository (or clone it):
   ```bash
   git clone https://github.com/purushottamkudale/GYM-management-System.git
   ```
2. **Copy the `gym` folder** into your server's root directory:
   - XAMPP: `xampp/htdocs/`
   - WAMP: `wamp/www/`
   - LAMP: `/var/www/html/`
3. **Open phpMyAdmin** at `http://localhost/phpmyadmin`
4. **Create a new database** named `gymdb`
5. **Import the database schema**: select the `gymdb.sql` file located in the `SQL File` folder of this repository
6. **Run the application** by navigating to `http://localhost/gym`

### Default Credentials

**Admin Login**
- Username: `admin@gmail.com`
- Password: `Test@12345`

**Employer/User Login**
- Username: `john@test.com`
- Password: `Test@123`
- *(Or register a new user account directly through the app)*

> ⚠️ **Security note:** These are demo credentials for local/academic use only. If you deploy this publicly, change the default admin password and remove or rotate the demo user account before going live.

## 📁 Project Structure

```
GYM-management-System/
├── SQL File/         # gymdb.sql — database schema and seed data
├── gym/              # Application source (PHP, JS, CSS)
└── Readme.txt         # Original setup notes
```

## 🤝 Contributing

This is a personal/academic project, but suggestions and feedback are welcome — feel free to open an issue.

## 📬 Contact

**Purushottam Kudale**
📧 purushottamkudale0@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/purushottam-kudale-0655492a2/)
