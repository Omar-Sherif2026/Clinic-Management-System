# 🏥 Clinic Management System (v3.0)

A comprehensive C++ Console Application for managing clinic operations, including patient records, appointment scheduling, search capabilities, and medical history tracking with automatic file persistence.

---

## 🌟 Key Features
- **File Persistence:** Automatically saves and loads all patient and appointment data to/from text files (`patients.txt` & `appointments.txt`).
- **Patient Management (CRUD):** Add, view, search, edit, and delete patient records. Deleting a patient automatically removes all associated appointments.
- **Appointment Scheduling:** Book appointments, update statuses (`Scheduled`, `Completed`, `Cancelled`), and view all scheduled visits.
- **Search & Medical History:** Quick search by patient name/ID/phone, and view full patient-specific medical history.
- **Input Validation:** Built-in safeguards against invalid user input and duplicate entries.

---

## 🛠️ Built With
- **Language:** C++
- **Concepts Used:** Object-Oriented Programming (OOP), Data Structures (`std::vector`), File I/O (`fstream`, `stringstream`), Strings & Algorithms.

---

## 💻 How to Run
1. Clone this repository or download `Clinic-Management-System`.
2. Compile using any C++ compiler:
   ```bash
   g++ Clinic-Management-System -o clinic
   ./clinic
