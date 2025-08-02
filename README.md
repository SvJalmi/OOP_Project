# OOP_Project
Digital Calender using C++ and OOP Concepts.

📅 Digital Calendar in C++
A Digital Calendar Application built using C++ that allows users to:

Print calendars (yearly & monthly)

Check today’s date

Calculate age

Add, Display, Edit, Remove Tasks

Set Reminders based on date

Search Tasks by Date

Check Leap Years

All tasks are saved persistently in a text file (tasks.txt).

🛠 Features
Calendar View: View full-year or month-specific calendars.

Current Date: Display today’s date.

Age Calculator: Calculate age based on birth year.

Task Management:

Add new tasks with date.

Display all tasks.

Edit tasks.

Remove tasks.

Reminders: Check if you have any tasks for the current day.

Search Tasks by Date.

Leap Year Checker.

📂 File Structure
bash
Copy
Edit
Digital-Calendar/
│
├── tasks.txt           # Stores tasks persistently
├── calendar.cpp        # Main C++ source code
└── README.md           # Project Documentation (This file)
🖥️ How to Run
Prerequisites:
C++ Compiler (G++ or any IDE like CodeBlocks, Dev-C++, Visual Studio)

Steps:
Clone or download this repository.

Make sure calendar.cpp and tasks.txt are in the same directory.

Open terminal (or IDE terminal) in that directory.

Compile the code:

bash
Copy
Edit
g++ calendar.cpp -o calendar
Run the executable:

bash
Copy
Edit
./calendar     # For Linux/Mac
calendar.exe   # For Windows (or just double-click the EXE file)
📄 Usage Instructions
Upon running, a menu will be displayed:

mathematica
Copy
Edit
1. Print Calendar
2. Check Today's Date
3. Calculate Age
4. Add/Display/Remove Tasks
5. Check for Leap Year
6. To Search Task
7. Reminder
8. Exit
You can navigate through various functionalities by entering respective choices.

Task Storage
All tasks are saved in tasks.txt file.

Format: DD/MM/YYYY: Task description

📝 Example
mathematica
Copy
Edit
Enter Your Choice: 4

1. Add New Task
2. Display All Tasks
3. Remove Task
4. Edit Task

Enter Your Choice: 1
Enter the task: Submit Project Report
Enter the date for the task (DD/MM/YYYY): 05/08/2025
Task added successfully!
📌 Key Concepts Used
Object-Oriented Programming (Classes & Static Methods)

File Handling (fstream)

Time & Date (ctime)

Arrays & Vectors for Task Management

Switch-Case Menus

🚀 Future Enhancements
Categorize tasks (e.g., Work, Personal, Meeting).

Task Notifications in real-time.

GUI-based interface using Qt/other frameworks.

Recurring task support.

Save tasks in JSON/Database for structured management.

🧑‍💻 Author
Shreya Jalmi
[NIT Goa | GirlScript Summer of Code Contributor]
GitHub: @SvJalmi

🖇 License
This project is for learning purposes and open-source. Feel free to fork and modify.


