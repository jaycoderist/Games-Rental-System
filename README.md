# 🎮 Games Rental System

An application where users can rent games, track their rentals, and view available games. All data is stored in a MySQL database for easy management and organization.

---

## 📌 Features

- 🔐 User Login and Registration System
- 🎮 View Available Games
- 🛒 Rent Games Easily
- 📋 Track Current and Previous Rentals
- 👨‍💼 Admin Management Panel
- ➕ Add and Manage Games
- 👥 Manage Users and Customer Orders
- 💾 MySQL Database Integration

---

## 🛠️ Built With

- **Visual Basic .NET (VB.NET)**
- **Windows Forms**
- **MySQL Database**
- **Visual Studio**

---

## 📂 Project Structure

```bash
GamesRentalSystem/
│
├── AddGameFormM.vb
├── AddUsersForm.vb
├── AdminPage.vb
├── LoginForm.vb
├── SignUpForm.vb
├── UserAddRentForm.vb
├── DatabaseConnection.vb
├── App.config
└── GamesRentalSystem.vbproj
```

---

## ⚙️ Installation Guide

### 1. Open the Project

- Open **Visual Studio**
- Select `GamesRentalSystem.vbproj`

### 2. Setup the Database

1. Open **MySQL** or **phpMyAdmin**
2. Create a new database
3. Import the provided SQL file (if available)
4. Update the database credentials inside:

```vb
DatabaseConnection.vb
```

Example:

```vb
server=localhost;
userid=root;
password=your_password;
database=games_rental_db;
```

### 3. Run the Application

Press:

```bash
Start / F5
```

---

## 🧩 Main Modules

### 👤 User Side

- Register an account
- Login securely
- Browse available games
- Rent games
- Track rental records

### 👨‍💼 Admin Side

- Add new games
- Manage users
- Monitor customer rentals
- Update game availability

---

## 💽 Database

The system uses a **MySQL Database** to store:

- User Accounts
- Game Information
- Rental Records
- Orders and Transactions

This helps keep data organized and easy to manage.

---

