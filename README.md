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
<pre> 📦 AirlineReservationSystem ├── 📄 main_project.c → Main menu and overall program control ├── 📄 registration.c → Handles user sign-up, login, and credential storage ├── 📄 admin.c → Admin dashboard for managing flights and bookings ├── 📄 user.c → Booking, viewing, modifying, and cancelling flights ├── 📄 validation.c → Input checks, flight/date validation, and login verification │ └── 📂 DataFiles/ ├── flight.txt → Stores flight records: numbers, origins, destinations, timings ├── user_info.txt → Registered user credentials (username & password) └── user_bookings.txt → Logs user bookings: flight details, seats, classes, etc. </pre>




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
| **Faizan Basheer**      | Login/Registration, Admin Panel, Flight CRUD |
| **Syed Muhammad Sufyan**| Booking/Canceling, Auto Flight Cleanup       |
| **Abdur Rehman Khan**   | Data Validation, User Data Presentation      |

---

## 🎯 **Why This Project?**
> Designed to emulate a real-world airline booking environment, this system gave us hands-on experience in:
> - 🔁 File Handling
> - 🧠 Logical Structuring
> - 🧩 Modular Programming
> - 🛠 Error Detection & Input Validation

---

## 📜 **License**
This project is **open-source** and intended for educational use only.  
Feel free to fork, learn, and build your own ideas on top of this.

---

## 🌐 **Connect With Us**

- 📧 **Abdur Rehman Khan:** [abdurrehmankhan0909@gmail.com](mailto:abdurrehmankhan0909@gmail.com)  
- 💼 **LinkedIn:** [Abdur Rehman Khan](https://www.linkedin.com/in/abdur-rehman-khan)

---

> ✨ *“Code is like humor. When you have to explain it, it’s bad.”* — Cory House

