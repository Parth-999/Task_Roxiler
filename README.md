# Task_Roxiler
# Store Rating System

A full-stack web application that allows users to register, log in, and submit ratings for stores. Built with **React.js**, **Express.js**, and **PostgreSQL**, the platform supports different functionalities based on user roles: Admin, Normal User, and Store Owner.

---

##  Features

###  Authentication
- Secure registration and login for all users.
- JWT-based authentication for protected routes.

###  User Roles
1. **System Administrator**
   - Add new users and stores.
   - View and filter all users and stores.
   - View overall statistics (total users, stores, ratings).

2. **Normal User**
   - Register, login, and rate stores (1–5 stars).
   - View all stores, search by name/address.
   - Edit their own submitted ratings.

3. **Store Owner**
   - View users who rated their store.
   - View average store rating.

---

##  Tech Stack

| Layer      | Technology        |
|------------|-------------------|
| Frontend   | React.js          |
| Backend    | Express.js (Node.js) |
| Database   | PostgreSQL        |
| Auth       | JWT + Bcrypt      |
| Styling    | Tailwind / CSS    |

---

##  Folder Structure

