# campus-connect-system
This Python program is a console-based College Management System that allows users to manage multiple colleges and their associated students and teachers. It uses Object-Oriented Programming (OOP) principles such as inheritance and encapsulation.
 Features
➕ Create new colleges (with duplicate checking)

👨‍🎓 Add students with roll number, name, and branch

👨‍🏫 Add teachers with roll number, name, and subject

📋 Display all students of a specific college

📋 Display all teachers of a specific college

🖥️ Console-based interactive user interface

🏗️ Classes Used
person: Base class for both students and teachers

student: Inherits from person, adds branch

teacher: Inherits from person, adds subject

college: Maintains lists of students and teachers, supports adding and displaying them

🚀 Getting Started
Prerequisites
Python 3.x installed on your system

Run the Program
bash
Copy
Edit
python college_management_system.py
Example Menu Output
markdown
Copy
Edit
Choose the Required option: 
1. Create College.
2. Add Student.
3. Add Teacher.
4. Display Students.
5. Display Teachers.
6. Exit.
💡 Sample Functional Flow
Create a new college.

Add multiple students and teachers under that college.

View the list of all students and teachers registered to that college.

🧠 Concepts Covered
Object-Oriented Programming

Inheritance and constructor chaining (super())

List management and searching

Basic CLI input/output
