# ✈️ **Airline Reservation System**

## 📖 **Project Overview**
The **Airline Reservation System** is a C-based console application developed as part of our *Programming Fundamentals Lab Project* at **FAST NUCES Karachi**. It facilitates complete management of airline operations including **user bookings**, **flight management**, and **administrative controls** — all within a **text-based user interface**.

---

## 💡 **Key Features**

### 👤 **User Features**
- 🔐 **Registration & Login**  
  Create a new account or log in as a registered user.
- 🔍 **Search Flights**  
  Filter flights based on origin, destination, and travel date.
- 🎫 **Book Tickets**  
  Reserve flights and choose ticket types (Economy/Business).
- 📋 **View Bookings**  
  See your upcoming or past reservations.
- ✏️ **Modify Bookings**  
  Update passenger count or change flight class.
- ❌ **Cancel Bookings**  
  Cancel individual or all upcoming reservations.

### 🛠️ **Admin Features**
- ✈️ **Flight Management**  
  Add, edit, or delete flight details (date, destination, seats, etc.).
- 📊 **Booking Overview**  
  View all passenger bookings or search by user.
- 🧹 **Auto-cleaning**  
  Automatically removes flights that have already departed.

---

## 🏗️ **System Architecture**
| File/Folder             | Type     | Description                                                               |
| ----------------------- | -------- | ------------------------------------------------------------------------- |
| `main_project.c`        | `C File` | 🔹 Entry point of the application; contains the main menu logic           |
| `registration.c`        | `C File` | 🔹 Handles user registration and login functionality                      |
| `admin.c`               | `C File` | 🔹 Admin-side operations: add, modify, delete, and view flights           |
| `user.c`                | `C File` | 🔹 User-side operations: search, book, modify, and cancel flight bookings |
| `validation.c`          | `C File` | 🔹 Provides input validations and checks flight availability              |
| `DataFiles/`            | `Folder` | 🔹 Directory containing external data used by the system                  |
| ├── `flight.txt`        | `Text`   | ➤ Stores all flight details: flight number, date, origin, destination     |
| ├── `user_info.txt`     | `Text`   | ➤ Stores registered user credentials (username & password)                |
| └─ `user_bookings.txt` | `Text`   | ➤ Tracks each user's booking history and related flight details           |





---

## 💻 **Tech Stack**
- 👨‍💻 **Language:** C (Standard C - GCC Compatible)
- 💻 **Compiler:** Dev C++ / Embarcadero / Code::Blocks
- 🗂 **Platform:** Windows OS
- ✍️ **IDE:** Any C-Compatible IDE

---

## ▶️ **How to Run**

1. 📥 **Download or Clone** this repository.
2. 📂 **Extract** and open the project folder.
3. 🧭 Open in **Dev C++** or any C IDE.
4. 🏁 **Press F11** to Compile & Run.

---

## 🧑‍🤝‍🧑 **Contributors**

| 👨‍💻 Name                | 🌟 Contribution Highlights |
|-------------------------|----------------------------|
| **Faizan Basheer**      | Login/Registration, Admin Panel, Flight CRUD Ops |
| **Syed Muhammad Sufyan**| Booking/Canceling, Auto Flight Cleanup       |
| **Abdur Rehman Khan**   | Data Validation, Specific User Data Presentation      |

---

## 🎯 **Why This Project?**
> Designed to emulate a real-world airline booking environment, this system gave us hands-on experience in:
> - 🔁 File Handling
> - 🧠 Logical Structuring
> - 🧩 Modular Programming
> - 🛠 Error Detection & Input Validation

---
## 📫 Contact

- 📧 Gmail: [_abdurrehmankhan0909@gmail.com_](mailto:abdurrehmankhan0909@gmail.com)  
- 🔗LinkedIn: [_Abdur Rehman Khan_](https://www.linkedin.com/in/abdur-rehman-khan-999198320?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

  
## 📜 **License**
This project is **open-source** and intended for educational use only.  
Feel free to fork, learn, and build your own ideas on top of this.

---
 

> ✨ *“Code is like humor. When you have to explain it, it’s bad.”* — Cory House

