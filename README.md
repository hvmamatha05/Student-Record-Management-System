# Student-Record-Management-System

Objective
A CLI-based CRUD system to manage student records using Java.

Tools Used
Java
Notepad
Terminal / Command Prompt

Concepts Covered

Classes and Objects
Collections (ArrayList)
Loops and conditionals
Encapsulation (fields inside Student class)
Constructor usage
Scanner for user input

How to Run
javac StudentManagement.java
java StudentManagement
Features

Add a new student (ID, Name, Marks)
View all students
Update student details by ID
Delete student by ID
Menu-driven loop using do-while

Project Structure
StudentManagement.java
  ├── class Student       → holds id, name, marks + display()
  └── class StudentManagement → main() + CRUD methods
  
Sample Output
--- Student Record System ---
1. Add Student
2. View All Students
3. Update Student
4. Delete Student
5. Exit
Enter choice: 1
Enter ID: 101
Enter Name: Mamatha
Enter Marks: 88.5
Student added successfully.
Key Learnings

How ArrayList stores and manages objects
How to loop through a list and match by ID
Difference between arrays and ArrayList
Use of static methods for menu operations
