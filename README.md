# E-shopping-store
E-commerce-website 

# 🏋️‍♂️ Gym Management System

A dynamic web application built using **Flask** with role-based access control, JWT authentication, and MySQL integration. It allows admins to manage memberships and classes, and users (members/trainers) to sign up, enroll in classes, and view personal profiles.

---

---

## 📦 Features

- 🔐 JWT Authentication (Stored in cookies)
- 🧑‍💼 Role-based Access Control (Admin / Member / Trainer)
- 📝 Membership & Class Management
- 👥 User Registration with Optional Class Enrollment
- 👤 Member & Trainer Profiles
- 💻 MySQL Integration 
- ✨ Clean UI with Flask templates

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Database**: MySQL
- **Authentication**: JWT (using `flask-jwt-extended`)
- **Frontend**: HTML, CSS (Jinja Templates)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ujjwal154/E-shopping-store/tree/main
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```
---

## 🧪 Run the Application Locally

```bash
python app.py
```

App will start on: `http://127.0.0.1:5000`

---

## 🔐 Roles & Pages

| Role     | Access                                   |
|----------|------------------------------------------|
| Admin    | Dashboard, Add Memberships, Manage Users |
| Member   | Dashboard, Enroll in Classes, Profile    |
| Trainer  | View Profile, Assigned Classes           |

---

## 🗃️ Database Schema

SQL initialization script is provided:  
📄 `UJJWAL.session.sql`

Includes tables:
- `user_details`
- `roles`, `roles_users`
- `classes`, `memberships`, `user_memberships`
- `enrollments`

---

## 🧠 Important Routes

- `/` – Home Page (Memberships Overview)
- `/signup` – Register as user with role & optional class
- `/login` – Log in and receive JWT
- `/grand` – Dashboard after login
- `/add_membership` – Admin-only: Create memberships
- `/profile` – Profile page for members/trainers
- `/logout` – Securely log out

## 👨‍💻 Author

**Ujjwal Dhiman**  
[LinkedIn Profile](https://www.linkedin.com/in/your-link/)  
📧 Email: your.email@example.com

---

## 🛡️ License

This project is licensed under the MIT License.  
Feel free to use and modify with credits.

