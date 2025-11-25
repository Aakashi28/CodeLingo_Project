# CodeLingo – Online Language Learning Platform  
A GUI-based Java project using Swing and MySQL, designed to support structured language learning through lesson creation, user management, and progress tracking.

---

## 📌 Abstract  
CodeLingo is a Java Swing–based language learning platform integrated with MySQL using JDBC. It supports role-based access for Admins, Instructors, and Learners. The system uses OOP concepts, collections, multithreading, and DAO-based database operations to deliver a simple and effective lesson management and progress-tracking experience.

---

## 🎯 Problem Statement  
Traditional language learning lacks proper lesson management and progress tracking. This project offers a simple Java-based GUI system where admins manage users, instructors create lessons, and learners track their progress through a connected MySQL database.

---

## 🎯 Objectives  
- Provide a simple GUI platform for learning languages.  
- Enable admins to manage users.  
- Allow instructors to create and organize lessons.  
- Allow learners to view lessons and track progress.  
- Integrate Java Swing with MySQL using JDBC for data handling.

---

## 🧩 System Architecture  
The platform follows a three-layer architecture:  
- **GUI Layer:** Java Swing user interface  
- **Logic Layer:** Services, OOP classes, and application logic  
- **Database Layer:** JDBC connection to MySQL storing users, lessons, and progress  

---

## 🧠 OOP Concepts Used  
- **Inheritance:** Admin, Instructor, and Learner classes extend a base User class  
- **Polymorphism:** Each user type displays its own dashboard  
- **Abstraction:** Shared attributes/methods defined in an abstract User class  
- **Interfaces:** Learner implements the ProgressTrackable interface  
- **Encapsulation:** Data access controlled via getters/setters  

---

## 🗄️ JDBC & Database Design  
The project uses JDBC to connect the Java application with a MySQL database.  
DAO classes perform operations on three main tables:  
- **users**  
- **lessons**  
- **progress**  

This ensures secure, modular, and efficient data handling.

---

## 🔧 Functional Modules  
### **Admin Module**
- Manage users  
- View system activity  

### **Instructor Module**
- Create lessons  
- Support learners  

### **Learner Module**
- View lessons  
- Track learning progress  

---

## 🌟 Key Features Implemented  
- Java Swing GUI for all interfaces  
- Role-based dashboards (Admin, Instructor, Learner)  
- Lesson creation and viewing  
- Progress tracking with auto-save  
- MySQL integration using JDBC  
- Use of OOP, Collections, and Multithreading  

---

## ✔️ Conclusion  
This project implements a functional language learning system using Java Swing and MySQL. By applying OOP concepts, JDBC, collections, and multithreading, it delivers a clean and user-friendly platform for lesson management and progress tracking.

---

## 📂 Project Structure  

