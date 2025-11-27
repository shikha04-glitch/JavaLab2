# LAB_ASSIGNMENT 2  
## 📘 Student Management System – Java OOP Project

A fully functional **Student Management System** implemented in **Java**, demonstrating key OOP concepts such as Inheritance, Abstract Classes, Interfaces, Polymorphism, Method Overloading, Method Overriding, and Collections (HashMap).  
The project follows a clean **package structure** (`model` & `service`) ensuring modular and maintainable code.

---

## 🚀 Features
- ✔️ **Add Student** – Stores unique student data using a `HashMap`  
- ✔️ **Delete Student** – Removes student using roll number  
- ✔️ **Search Student** – Displays full student details  
- ✔️ **Update Student** – Updates marks/course and recalculates grade  
- ✔️ **View All Students** – Shows all records  
- ✔️ **Method Overloading** – `displayInfo()` overloaded in `Student`  
- ✔️ **Method Overriding** – `displayInfo()` overridden from `Person`  
- ✔️ **Interface Implementation** – CRUD operations defined in `RecordActions`/implemented in `StudentManager`  

---

## 🧩 OOP Concepts Used
| OOP Concept          | Status |
|----------------------|--------|
| Inheritance          | ✅ |
| Method Overloading   | ✅ |
| Method Overriding    | ✅ |
| Abstract Class       | ✅ |
| Interface            | ✅ |
| Polymorphism         | ✅ |
| Encapsulation        | ✅ |
| Collection Framework | ✅ |

---

## 📂 Project Structure
JavaLabAss2/
└── src/
├── Main.java
├── model/
│ ├── Person.java
│ └── Student.java
└── service/
├── RecordActions.java
└── StudentManager.java

---

## 🖥️ Sample Output

```plaintext
Student Added Successfully
Student Added Successfully

--- All Students ---

Student Info:
Roll No: 101
Name: Ankit
Email: ankit@mail.com

Course: B.Tech
Grade: A+

Student Info:
Roll No: 102
Name: Riya
Email: riya@mail.com

Course: M.Tech
Grade: A

---

👩‍💻 Author
**Shikha**  
B.Tech CSE – K.R. Mangalam University
