# 🔐 Cyber Management System — C Project

A console-based **Cyber Management System** written in C.  
This system manages user login records, tracks session duration, and provides admin functionalities such as inserting, viewing, searching, and deleting user records.

---

## 📁 Project File

- **Fsprojectcyber.cpp** (source code)  
  *(Uploaded from original file)*

---

## 🚀 Features

### 👨‍💼 Admin Panel
Admin Credentials:
- **Username:** `CyberManagement`
- **Password:** `Group12`

Admin can:
- Insert new user records  
- View all stored records  
- Search for a specific user  
- Delete user records  
- View login date/time  
- Track session duration  

---

### 👤 User Panel
Users can:
- Sign up (stored in `login.txt`)
- Login and view their record
- Check their login duration

---

### ⏱ Login Time Tracking
The system stores:
- Login date  
- Login time  
- Auto-calculated session duration  
- Alerts the admin if a user exceeds **5 hours** (300 minutes):  
  **"ALERT!!! MALICIOUS ACTIVITY"**

---

## 💾 Data Storage

### Files created/used:
- **cyber.txt** → Stores user ID, name, date, time  
- **cyber1.txt** → Temporary file for deletion  
- **login.txt** → Stores user login credentials  

All data is stored automatically through file handling (`fopen`, `fprintf`, `fscanf`).

---

## 🛠 Technologies Used

- C programming  
- File handling (`stdio.h`)  
- String handling (`string.h`)  
- Time manipulation (`time.h`)  
- Windows console commands:
  - `system("CLS")`
  - `system("color")`
- Basic calculations for duration tracking

---

## ▶️ How to Run

1. Open **CodeBlocks**, **Dev C++**, **Turbo C**, or **VS Code** with a C compiler.
2. Create a new project.
3. Add the file **Fsprojectcyber.cpp**.
4. Build & run the program.
5. The system will automatically create required `.txt` files.

---

## 📘 Program Flow

### 1️⃣ Start Screen  
→ Login as Admin  
→ Login / Sign-up as User  

### 2️⃣ Admin Menu  
- Insert Record  
- Display All Records  
- Search Record  
- Delete Record  
- Exit  

### 3️⃣ User Menu  
- View User Record  
- Exit  

---

## 🎯 Learning Outcomes

- Building a menu-driven C application  
- File handling operations  
- Performing date-time calculations  
- Implementing admin-user access levels  
- Designing modular functions in C  

---

## 📝 Author Notes

This project demonstrates a complete mini cyber-management workflow suitable for:
- College projects  
- Portfolio building  
- Learning file handling & authentication logic  
- Practicing modular C programming  

---

## 📦 Source Code Reference

This README corresponds to the code in:  
**`Fsprojectcyber.cpp`**
