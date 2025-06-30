# ✈️ Airline Reservation System

## 📘 Project Report  
**Course:** Programming Fundamentals – Lab  
**Campus:** FAST-NUCES, Karachi  
**Section:** BCS-1G  
**Submission Date:** 4th December 2024  
**Lab Instructor:** Miss Ramsha Iqbal


---

## 👥 Group Members

| Name                  | Student IDs     | Key Roles                                                                 |
|-----------------------|------------|----------------------------------------------------------------------------|
| **Faizan Basheer**     | 24K-0571   | Login system, Admin dashboard, Flight management (Add/Delete/Modify)      |
| **Syed Muhammad Sufyan** | 24K-0806 | Booking system, Auto flight cleanup, User-side flight operations           |
| **Abdur Rehman Khan**  | 24K-0767   | Input validation, error handling, specific user display & data filtering   |

---

## 🎯 Motivation

In an age where air travel is a core component of global connectivity, our goal was to simulate a simplified version of an airline reservation system. This project seeks to streamline user booking processes while giving administrators flexible control over flight management, mirroring real-world airline systems within a C-based console application.

---

## 🛠️ Tools & Technologies

- **Language:** C
- **Compiler:** Dev C++ / Embarcadero
- **Data Handling:** Text file-based persistence (`.txt`)
- **Testing:** Manual functional testing for each module

---

## 🚀 System Overview

The **Airline Reservation System (ARS)** is a modular C program that enables:

- Secure user registration and authentication
- Flight search & booking features
- Dynamic admin panel for real-time flight management
- Comprehensive booking modifications, cancellations, and viewing

---

## 🔐 Login Menu Functionalities

| Feature             | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **Registration**     | Collects & validates user credentials, email, phone, DOB, gender           |
| **User Login**       | Authenticates existing users                                                |
| **Admin Login**      | Grants privileged access using preset credentials (`admin` / `1234`)       |
| **Forgot Password**  | Recovers password via email+username matching                              |
| **Exit**             | Terminates program with clean shutdown                                     |

✔ All data is persistently stored using structured text files.  
✔ User credentials are stored in `user_info.txt`.

---

## 👤 User Menu Features

| Feature               | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| **User Details**       | Displays profile info (DOB, age, contact, gender)                          |
| **View Flights**       | Lists valid flights from `flight.txt`, deletes expired ones automatically |
| **Book Flight**        | Books available flights with seat class and ticket count                   |
| **View Bookings**      | Displays all reservations for current user                                 |
| **Modify Bookings**    | Allows change of class or ticket count                                     |
| **Cancel Booking**     | Removes selected booking and updates file                                  |
| **Logout**             | Logs user out of the session                                               |

---

## 🧑‍✈️ Admin Panel Features

| Feature                | Description                                                                 |
|------------------------|------------------------------------------------------------------------------|
| **Add Flight**          | Add flight info: number, origin, destination, departure details             |
| **Delete Flight**       | Remove expired/canceled flights, auto-update user bookings                 |
| **Modify Flight**       | Edit date/time of an existing flight and reflect changes in bookings       |
| **View All Bookings**   | Admin overview of all flight bookings across users                         |
| **Search Bookings**     | Find bookings based on flight number or user ID                            |
| **Logout**              | Exits the admin session cleanly                                            |

✔ Bookings are stored in `user_bookings.txt`.  
✔ Flights are stored in `flight.txt`.  
✔ Data updated using temporary files for safety and rollback.

---

## 📁 File Architecture

| File Name              | Purpose                                                                 |
|------------------------|-------------------------------------------------------------------------|
| `main_project.c`       | Main driver file (login menu, system navigation)                        |
| `registration.c`       | Manages registration, user login, admin login, and password recovery    |
| `admin.c`              | Controls admin features: flight CRUD and global booking view            |
| `user.c`               | Contains functions for search, booking, canceling, modifying flights     |
| `validation.c`         | Handles input checks, data filtering, and expired flight deletion       |
| `flight.txt`           | Stores flight data (origin, destination, timing)                        |
| `user_info.txt`        | Records user credentials and personal data                              |
| `user_bookings.txt`    | Tracks booking info for all users                                       |

---

## 💡 Key Highlights

- 👥 Role-based interaction: admin and user modes with different permissions
- 📦 File persistence ensures bookings survive restarts
- 🔐 Input validation & password security enforced
- 🧹 Automatic cleanup for expired flights improves accuracy
- 🧾 Modular, clean codebase built around reusability

---

## 🔍 Challenges Faced

- Designing a secure registration/authentication flow using file handling
- Ensuring correct synchronization between flight deletions and user bookings
- Preventing data loss during modification with temporary file swap mechanism
- Designing a console-based experience that feels structured and interactive

---

## 📜 Conclusion

This Airline Reservation System represents a microcosm of real-world airline software. Though built in C, it lays a strong foundation in:

- Data structures & file manipulation
- Control flow and validation logic
- Modular menu-driven programming

> ✨ “What began as a lab assignment, turned into an immersive journey | teaching us not just about code, but about clarity, modularity, and responsibility.”

---

## 🔮 Future Scope

- 🌐 Add a Graphical User Interface (GUI)
- 📡 Connect with real-time APIs for live flight data
- 🧩 Switch to databases (SQLite/MySQL) for scalable data handling
- 📧 Add email notifications for bookings and cancellations

---

## 📬 Contact Us

- 📧 Email: [abdurrehmankhan0909@gmail.com](mailto:abdurrehmankhan0909@gmail.com)  
- 📧 Email: [isyedsufyan2005@gmail.com](mailto:isyedsufyan2005@gmail.com) 

---
### 💬 Feedback & Suggestions

We warmly welcome your thoughts | feel free to share any ideas or suggestions to help us improve and enhance this project further.

---
## 🪪 License

This project is open-source and intended for **educational use only**.  
Redistribution for commercial purposes is not permitted.

---
