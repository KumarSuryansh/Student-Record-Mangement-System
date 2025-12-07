# 📘 Student Record Management System

A File-Based Student Database Manager built using C++ (OOP + File Handling)

---

## 🚀 Overview

The **Student Record Management System (SRMS)** is a menu-driven C++ application designed to efficiently **store, retrieve, update, search, and delete student records**.
Unlike manual record-keeping or spreadsheet-based systems, this project provides:

* Structured data handling
* Permanent file storage
* Clean tabular output
* Error-free, validated input
* Modular design using Object-Oriented Programming

This project implements real-world concepts of **classes, objects, encapsulation, vectors, and file handling**, making it a beginner-friendly yet powerful application.

* **Course:** CSE 201 – Coding Skills
* **Institution:** SRM University–AP
* **Academic Year:** 2025–26

---

## ✨ Key Features

### 🔹 1. Persistent Storage

All records are stored in **students.txt**, ensuring data is never lost when the program closes.

### 🔹 2. Complete CRUD System

* Add new student
* Display all students
* Search by Student ID
* Update details
* Delete a record

### 🔹 3. Validated Input

Protects against invalid age, GPA, or malformed IDs using safe input buffering and validation.

### 🔹 4. Clean, Formatted Table Output

Uses `iomanip` and custom table functions (`setw()`, divider lines) for professional-looking CLI tables.

### 🔹 5. Fully Modular OOP Architecture

* `Student` class → Holds individual records
* `StudentManagementSystem` class → Controls database operations
* Each feature separated into functions for better readability and maintainability

---

## 🛠️ Tech Stack

* **Language:** C++
* **Paradigm:** Object-Oriented Programming
* **Storage:** File Handling (`fstream`)
* **Data Structure:** `vector<Student>`
* **Libraries Used:**

  * `<iostream>`
  * `<fstream>`
  * `<iomanip>`
  * `<string>`
  * `<vector>`
  * `<limits>`

---

## ⚙️ System Workflow

1. **Program Start**

   * Loads existing data from `students.txt`.
   * Converts each line into a `Student` object.

2. **User Menu**

   * Add
   * Display
   * Search
   * Update
   * Delete
   * Exit

3. **Record Operations**

   * Uses vector for in-memory storage.
   * Writes updated data back to the file after every change.

4. **Program Exit**

   * Auto-saves all records.
   * Displays exit message.

---

## 📂 File Structure

```
📁 Student-Record-Management-System
 ├── main.cpp
 ├── Student.h / Student.cpp
 ├── StudentManagementSystem.h / StudentManagementSystem.cpp
 ├── students.txt
 └── README.md
```

---

## 📦 Installation & Usage

### 🔧 Prerequisites

* A C++ compiler (G++ recommended)

### 🧩 Clone the Repository

```bash
git clone https://github.com/KumarSuryansh/Student-Record-Mangement-System.git
cd Student-Record-Mangement-System
```

### ⚙️ Compile the Program

```bash
g++ main.cpp -o srms
```

### ▶️ Run the Program

**Windows**

```bash
srms.exe
```

**Mac/Linux**

```bash
./srms
```

---

## 📊 Sample Output

### 🎯 Add Student

```
Enter Student ID: AP2411001
Enter Name: Rahul Kumar
Enter Age: 19
Enter Course: CSE
Enter GPA: 8.7
Record Added Successfully!
```

### 📜 Display All Students

```
------------------------------------------------------------
| ID           | Name          | Age | Course | GPA        |
------------------------------------------------------------
| AP2411001    | Rahul Kumar   | 19  | CSE    | 8.7        |
------------------------------------------------------------
```

### 🔍 Search Student

```
Enter ID to Search: AP2411001
Record Found:
AP2411001  Rahul Kumar  19  CSE  8.7
```

### ✏️ Update Record

```
Enter ID: AP2411001
1. Update Name
2. Update Age
3. Update Course
4. Update GPA
5. Update All
```

### ❌ Delete Student

```
Enter ID to Delete: AP2411001
Are you sure? (Y/N): Y
Record Deleted Successfully!
```

---

## 📘 Concepts Demonstrated

### 🧱 Object-Oriented Programming

* Classes & Objects
* Encapsulation
* Getter/Setter methods
* Reusable modules

### 📂 File Handling

* Reading and writing using ifstream/ofstream
* Persistent storage
* Data serialization

### 🧮 Data Structures

* Vector as a dynamic storage system
* Safe searching and indexing

### 🛡️ Input Validation

* Clearing input buffer
* Valid ID format checking
* Preventing invalid numeric input

---

## 👥 Team Members (SRM University AP)

| Name               | Registration No.  | 
| ------------------ | ----------------- | 
| Om Mittal          | AP24110010404     | 
| **Suryansh Kumar** | **AP24110010446** | 
| G. Sri Sujan       | AP24110010413     | 
| Piyush Raj         | AP24110010439     | 
| I. Terish Charan   | AP24110010412     | 
| S. Pranav Saket    | AP24110010407     | 

---

## 📝 Conclusion

This project bridges the gap between theoretical learning and real-world software development.

By applying:

* OOP
* File handling
* Input validation
* Modular design

You have built a reliable, extendable system that can evolve into:

* A GUI-based tool
* A MySQL/SQLite-powered database system
* A system with sorting, filtering, and analytics
* A secure, authentication-based application

It forms a strong foundation for more advanced student management solutions.

---
