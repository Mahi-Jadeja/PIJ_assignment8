# PIJ_assignment8


# 📚 Student Data Entry Application

A menu-driven Java program for managing student records using Object-Oriented Programming (OOP) concepts. This application allows adding, viewing, updating, searching, and deleting student details, implemented with modular Java files and custom exceptions.

---

## 👨‍🎓 Author Info

- **Name:** Mahi Jadeja  
- **PRN:** 23070126068
- **Branch:** AIML A-3  
- **Batch:** 23-27  

---

## ✨ Features

- Add student with PRN, name, DoB, and marks
- Display all students
- Search student by:
  - PRN
  - Name
  - Position in the list
- Update existing student details
- Delete student records
- Robust error handling with **custom exceptions**
- Clean, modular code following Java best practices

---

## 🛠️ Technologies Used

- Java (OOP, Exception Handling, Collections)
- Custom Exception Classes
- CLI-based interaction

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-data-entry.git
   cd student-data-entry
2. javac Assignment_8/*.java
3. java Assignment_8.Main

## 📂 File Structure

student-data-entry/
│
├── Main.java                     # Handles menu and user interaction  
├── Student.java                  # Defines the Student class and attributes  
├── StudentManager.java           # Manages all operations (add, update, delete, search)  
├── InvalidDataException.java     # Custom exception for validation errors  
├── StudentNotFoundException.java # Custom exception for missing records  
└── README.md                     # Project documentation  


## ⚠️ Exception Handling

This project uses two custom exception classes to improve reliability and ensure clean error handling:

- **InvalidDataException**  
  Thrown when:
  - A student's marks are invalid (not in 0–100 range)
  - Any required input (like PRN or Name) is left empty

- **StudentNotFoundException**  
  Thrown when:
  - A student is searched by PRN or Name and is not found
  - An invalid position is accessed in the student list
  - A student is being updated or deleted but doesn't exist

-**Output Preview**
===== Student Data Entry Menu =====
1. Add Student
2. Display All Students
3. Search by PRN
4. Search by Name
5. Search by Position
6. Update Student
7. Delete Student
8. Exit


## 📌 Notes
Ensure all Java files are under the same Assignment_8 package/folder.

Exception handling helps the program run smoothly even with incorrect inputs.

The program uses ArrayList for dynamic student record management instead of static arrays.

## 📎 License
This project is for educational use and lab submission purposes only.
