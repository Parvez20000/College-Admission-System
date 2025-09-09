# 🎓 College Admission System (Java + JDBC + MySQL)

This is a simple **Java Console Application** for managing college admissions using **JDBC and MySQL**.  
It allows adding students, adding courses, applying for admissions, and viewing admission status based on cutoff marks.

---

## 📌 Features
- ➕ Add Students  
- ➕ Add Courses  
- 📝 Apply for Admission (auto-check cutoff marks)  
- 📋 View All Admissions  

private static final String USER = "root";      // your MySQL username
private static final String PASSWORD = "";      // your MySQL password
javac CollegeAdmissionSystem.java
java -cp .:mysql-connector-j.jar CollegeAdmissionSystem

## File structure
CollegeAdmissionSystem/
 ├── CollegeAdmissionSystem.java   # Main Java code
 ├── college_admission.sql         # Database SQL script
 └── README.md                     # Documentation

## Example Menu
 --- College Admission System ---
1. Add Student
2. Add Course
3. Apply for Admission
4. View Admissions
5. Exit


