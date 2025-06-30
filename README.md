# 🛫 **Airline Reservation System**  

## 📘 **About the Project**
The **Airline Reservation System** is a `C language` based terminal application developed as part of our ***Programming Fundamentals Lab Project*** at **FAST NUCES - Karachi**.  
It simulates a simplified airline service, empowering users and admins to manage flights, bookings, and passenger data where everything through a structured and file-driven interface.

---

## ⚙️ **Project Highlights**

### 👤 **User Panel**
- 🔐 **User Authentication** – Sign up or log in using your credentials  
- 🔍 **Flight Finder** – Search flights using departure, arrival, and travel date  
- 🎟️ **Reserve a Seat** – Book business or economy class tickets  
- 📄 **View Bookings** – Check your current or previous flight reservations  
- 🛠️ **Edit Bookings** – Update ticket quantity or class for any flight  
- ❌ **Cancel Reservations** – Instantly delete selected bookings

---

### 🛠️ **Admin Panel**
- ✈️ **Flight Controls** – Add, modify, or delete flights with full control  
- 📊 **Passenger Logs** – Access global booking information and passenger details  
- 🧹 **Auto Cleanup** – Automatically remove flights that are no longer valid

---

## 🗂 **File Structure**

| 📄 **File/Module**       | 🧠 **Purpose**                                                                 |
|--------------------------|--------------------------------------------------------------------------------|
| `main_project.c`         | 🧭 Central control file with main menu and redirection                         |
| `registration.c`         | 👤 Handles sign up / login authentication                                       |
| `admin.c`                | 🛫 Admin operations (flight add, edit, delete, view)                           |
| `user.c`                 | 🎫 Booking logic for users: view, cancel, modify bookings                      |
| `validation.c`           | 🧾 Input validation & flight availability checks                               |
| `DataFiles/`             | 📁 Folder containing persistent program data                                   |
| ├── `flight.txt`         | ✈️ Stores available flights                                                     |
| ├── `user_info.txt`      | 👥 Stores login credentials (username & password)                              |
| └── `user_bookings.txt`  | 🧳 Logs all booking records by users                                           |

---

## 💻 **Technology Stack**

- **Language:** C  
- **Compiler:** GCC / Embarcadero Dev C++  
- **Platform:** Windows OS  
- **IDE:** Code::Blocks / Dev C++ / Turbo C (Any C-supported IDE)  

---

## ▶️ **How to Run**

1. 📥 **Clone** or **Download** the repository  
2. 📂 **Open** the project folder in your IDE  
3. 🔧 **Compile all source files** (`.c`)  
4. 🏃 **Run** the executable and follow the on-screen menu

---

## 🧑‍🤝‍🧑 **Contributors**

| 👨‍💻 **Team Member**        | 🧠 **Responsibilities**                                                                                   |
|----------------------------|------------------------------------------------------------------------------------------------------------|
| **Faizan Basheer**         | 🔸 Built the complete **login & registration system** <br> 🔸 Developed the **Admin Dashboard & Flight CRUD** logic |
| **Syed Muhammad Sufyan**   | 🔸 Designed the **User-side booking, modification, and cancellation** logic <br> 🔸 Implemented **auto-flight cleanup** |
| **Abdur Rehman Khan**      | 🔸 Wrote **data validation modules** <br> 🔸 Developed logic to **extract and display user-specific booking history** |

---

## 🎯 **Why This Project?**

> This project offered practical exposure to core programming concepts like:
> - 🗃️ File Handling & I/O  
> - 🧩 Modular Programming Structure  
> - 🔐 Authentication Logic  
> - ❌ Error Management & Validation  
> - 📂 Data Persistence  

---

## 🧾 Final Words
## 🧾 Final Words

| What started as a simple lab assignment in the Programming Fundamentals course soon evolved into a full-fledged simulation of a real-world reservation system. 
| Through this journey, we didn't just write C code — we developed critical thinking, debugged with patience, and designed systems with structure and purpose. 
| Every module — from flight management to user bookings — taught us the value of logic, clarity, and clean architecture in programming. 
| This project was not only about learning syntax but about learning how to **think like programmers**, and more importantly, how to work like a team. 

| 🛫 *This Airline Reservation System is a symbol of our foundation — the first real step toward building software that solves problems.* 
| 💡 *Where menus met memory, and loops met logic — this project helped us evolve from coding students into budding developers.* 


---

## 📫 **Get in Touch**

- 📧 **Email:** [abdurrehmankhan0909@gmail.com](mailto:abdurrehmankhan0909@gmail.com)  
- 🔗 **LinkedIn:** [Abdur Rehman Khan](https://www.linkedin.com/in/abdur-rehman-khan-999198320)

---

## 📜 **License**

This project is **open-source** and developed solely for **educational use**.  
Feel free to **fork, learn, and expand** upon it for your own projects or academic needs.

---

> ✨ *"A user-friendly program is invisible, but powerful. That’s what this project aims to be."*  
> ✨ *“Code is like humor. When you have to explain it, it’s bad.”*  ~ Cory House
