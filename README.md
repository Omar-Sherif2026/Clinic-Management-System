![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Git](https://img.shields.io/badge/GIT-E44D27?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

# 🏥 Clinic Management System (v3.0 Ultra)

A comprehensive C++ Console Application for managing clinic operations, featuring formatted terminal UI, patient records, appointment scheduling, search capabilities, and medical history tracking with automatic file persistence.

---

## 🌟 Key Features
- **File Persistence:** Automatically saves and loads all data to/from text files (`patients.txt` & `appointments.txt`).
- **Patient Management (CRUD):** Add, view, search, edit, and delete patient records with unique ID generation.
- **Intelligent Cascade Deletion:** Deleting a patient automatically cleans up all associated appointments.
- **Appointment Lifecycle:** Track appointment status (`Scheduled`, `Completed`, `Cancelled`).
- **Search & Medical History:** Search patients instantaneously by Name/ID/Phone and view full patient history.
- **Formatted CLI:** Clean ASCII tables, ANSI colors, and status indicators for an enhanced terminal UI experience.

---

## 🖥️ Application Output & UI Preview

```text
--------------------------------------------
 🏥 نظام إدارة العيادة الطبية (v3.0 Ultra)
--------------------------------------------
1.  إضافة مريض جديد
2.  عرض قائمة المرضى
3.  البحث عن مريض
4.  تعديل بيانات مريض
5.  حذف مريض
6.  حجز موعد طبي
7.  عرض جدول المواعيد
8.  تعديل حالة موعد
9.  عرض السجل الطبي لمريض
10. خروج من البرنامج
اختر عملية (1-10): 2

================================ قائمة المرضى ================================
ID      Name                     Age       Phone             
-----------------------------------------------------------------------------
1       Omar Sherif              22        01012345678       
2       Ahmed Hassan             30        01198765432       
=============================================================================

=================================== جدول المواعيد ===================================
App ID  Patient Name         Date          Time      Doctor              Status      
----------------------------------------------------------------------------------------------------
1       Omar Sherif          2026-08-10    14:30     Dr. Youssef         Scheduled   
2       Ahmed Hassan         2026-08-11    16:00     Dr. Sarah           Completed   
====================================================================================================


🛠️ Built With
Language: C++

Concepts Used: Object-Oriented Programming (OOP), Data Structures (std::vector), File I/O (fstream, stringstream), Formatted I/O (iomanip).


💻 How to Run
1.  Clone this repository:
    git clone [https://github.com/YOUR_USERNAME/Clinic-Management-System.git](https://github.com/YOUR_USERNAME/Clinic-Management-System.git)


2.  Compile using any C++ compiler:
    g++ Clinic-Management-System.cpp -o clinic


3.  Run the application:
    ./clinic
