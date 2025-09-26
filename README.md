# CODEALPHA-Task1
Name: Tangrllapalli Srinivas
Company: CodeAlpha
Domain: Java Programing
Duration:Sep 1 to Sep 30


Overview of the project:- 


Project Title:

Student Grade Analyzer in Java

🎯 Project Objective:

To design a simple Java application that allows the user to input student grades, store them in an array, and calculate key statistics such as:

Average grade

Highest grade

Lowest grade

This helps in quickly analyzing the performance of a group of students.

🛠️ Core Features:
Feature	Description
📥 Input Collection	Takes the number of students and their grades as input
🧠 Grade Analysis	Calculates total, average, highest, and lowest grades
📊 Output Summary	Displays a detailed report with all grades and statistics
🔍 How It Works:
1. User Input:

Prompts the user to enter the total number of students.

Takes grade input for each student one by one using a loop.

2. Data Storage:

Stores grades in an integer array: int[] grades.

3. Grade Processing:

Iterates through the array:

Accumulates the total grade.

Checks and updates the highest and lowest grades.

4. Statistics Calculation:

Calculates average as:

average = (double) total / numStudents;

5. Output Report:

Displays:

Individual student grades

Average grade

Highest and lowest grades

🖥️ Sample Console Output:
Enter the number of students: 3
Enter grade for Student 1: 85
Enter grade for Student 2: 90
Enter grade for Student 3: 78

--- Student Grade Summary ---
Student 1: 85
Student 2: 90
Student 3: 78
Average Score: 84.33333333333333
Highest Score: 90
Lowest Score: 78

📦 Technologies Used:
Component	Details
Language	Java
Input	Scanner class for console input
Data Structure	Array (int[])
Looping	for loop and enhanced for-loop (for-each)
Package	Declared under org.example (can be modified based on project structure)
💡 Possible Enhancements:
Enhancement	Description
✅ Grade Validation	Ensure grades are between 0 and 100
✅ Letter Grades	Convert numerical grades to A/B/C/... format
✅ GUI Interface	Use JavaFX or Swing for graphical input/output
✅ Sorting	Sort students based on grades before displaying
✅ File Input/Output	Save or read grades from a text file
📚 Educational Value:

This project helps learners understand:

Array handling

Loops and conditions

Data processing logic

User interaction with console

Basic statistics in programming

If you'd like, I can help you:

Add letter grade calculation (A/B/C/D/F)

Sort the grades in descending order

Generate a printable report
