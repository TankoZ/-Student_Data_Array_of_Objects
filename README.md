# 🎓 Student Management System

This project is a **basic Java program** designed to **learn and practice Object-Oriented Programming (OOP) concepts** such as **encapsulation, abstraction, polymorphism, and modularity**. It provides a simple console-based system to **add, display, search, update, and delete student records**.

---

## 📖 Overview

The program uses a **menu-driven interface** for managing student data. Users can:

* Add a new student with PRN, Name, Date of Birth, and Marks.
* Display all students.
* Search students by PRN, Name, or position in the list.
* Update a student’s details.
* Delete a student record.

The project is designed using **classes** to represent `Student` and `StudentManager`, demonstrating **OOP principles**.

---

## 🛠 Features

* **Add Student** → Input student details and store in a dynamic list.
* **Display All Students** → List all students with their details.
* **Search Student** → By PRN, Name, or position.
* **Update Student** → Modify existing student information.
* **Delete Student** → Remove student by PRN.
* **Menu-driven** → Easy-to-use console interface.

---

## 🚀 How to Run

1. Clone or download the project.
2. Compile all `.java` files:

   ```bash
   javac *.java
   ```
3. Run the main program:

   ```bash
   java Main
   ```
4. Follow the on-screen menu to perform actions.

---

## 📂 Project Structure

```
.
├── Main.java          # Main menu-driven program
├── Student.java       # Student class with encapsulated attributes
├── StudentManager.java# Class handling all student operations
```

---

## ✨ Example Usage

```
Menu:
1. Add Student
2. Display All Students
3. Search by PRN
4. Search by Name
5. Search by Position
6. Update Student
7. Delete Student
8. Exit
Enter your choice: 1
Enter student details:
PRN: 22070126102
Name: Henil
Date of Birth: 01-01-2002
Marks: 85
Student added successfully!
```

---

## 🎯 OOP Concepts Demonstrated

* **Encapsulation** → Private fields with getters and setters in `Student` class.
* **Abstraction** → `StudentManager` class abstracts the management operations.
* **Polymorphism** → Methods handle students differently based on input.
* **Modularity** → Separate classes for data (`Student`) and operations (`StudentManager`).

---

## 👨‍💻 Author

* **Henil Shah**
* PRN: *22070126102*
* Batch: *2022-26*
