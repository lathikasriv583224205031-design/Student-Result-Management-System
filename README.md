📄 main.py – File Explanation

The "main.py" file is the core file of this project.
It contains all the logic required to manage student records.

🔹 1. Import Section

import os

- Used to check whether the file exists before reading data.

---

🔹 2. File Name Declaration

FILENAME = "students.txt"

- Stores all student records in this file.
- The file is automatically created when a student is added.

---

🔹 3. Grade Calculation Function

def calculate_grade(avg):

- Accepts average marks as input.
- Returns grade (A, B, C, D, or Fail) using conditional statements.

---

🔹 4. Add Student Function

def add_student():

- Takes student name, roll number, and 3 subject marks.
- Calculates:
  - Total marks
  - Average
  - Grade
- Saves data into "students.txt".
- Uses exception handling to avoid invalid inputs.

---

🔹 5. View Students Function

def view_students():

- Reads all records from the file.
- Displays:
  - Name
  - Roll Number
  - Total
  - Average
  - Grade
- Checks if file exists before reading.

---

🔹 6. Main Menu (Program Control)

while True:

- Displays menu options:
  1. Add Student
  2. View Students
  3. Exit
- Runs continuously until user chooses Exit.
- Uses conditional statements to call respective functions.

---

🧠 Concepts Used in main.py

- Functions
- Loops (while loop)
- Conditional Statements (if-elif-else)
- File Handling
- Exception Handling
- String Formatting

---

🎯 Purpose of main.py

This file controls the entire application workflow and connects all functions together to form a complete working system.
