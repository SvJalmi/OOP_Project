[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# 📅 Digital Calendar in C++


A **Digital Calendar Application** built using **C++ and OOP Concepts** that allows users to:

* Print calendars (yearly & monthly)
* Check today’s date
* Calculate age
* Add, Display, Edit, Remove Tasks
* Set Reminders based on date
* Search Tasks by Date
* Check Leap Years

All tasks are saved persistently in a text file (`tasks.txt`).

---

## 🛠 Features

* **Calendar View**: View full-year or month-specific calendars.
* **Current Date**: Display today’s date.
* **Age Calculator**: Calculate age based on birth year.
* **Task Management**:

  * Add new tasks with date.
  * Display all tasks.
  * Edit tasks.
  * Remove tasks.
* **Reminders**: Get reminders for tasks scheduled for the current date.
* **Search Tasks by Date**.
* **Leap Year Checker**.

---

## 📂 File Structure

```
OOP_Project/
│
├── tasks.txt           # Stores tasks persistently (Keep empty initially)
├── calendar.cpp        # Main C++ source code
└── README.md            # Project Documentation (This file)
```

---

## 🖥️ How to Run

### Prerequisites:

* C++ Compiler (G++, CodeBlocks, Dev-C++, Visual Studio, etc.)

### Steps:

1. **Clone or Download this Repository**.
2. Ensure `calendar.cpp` and `tasks.txt` are in the same directory.
3. Open Terminal/Command Prompt in that directory.
4. Compile the code:

   ```bash
   g++ calendar.cpp -o calendar
   ```
5. Run the executable:

   ```bash
   ./calendar     # For Linux/Mac
   calendar.exe   # For Windows (or double-click the EXE file)
   ```

---

## 📋 Usage Instructions

When you run the program, a menu will appear:

```
1. Print Calendar
2. Check Today's Date
3. Calculate Age
4. Add/Display/Remove Tasks
5. Check for Leap Year
6. To Search Task
7. Reminder
8. Exit
```

Navigate through the menu by entering the corresponding choice number.

---

### 🗃 Task Storage

* All tasks are saved in `tasks.txt`.
* Format:

  ```
  DD/MM/YYYY: Task description
  ```

---

## 📝 Example Usage

```
Enter Your Choice: 4

1. Add New Task
2. Display All Tasks
3. Remove Task
4. Edit Task

Enter Your Choice: 1
Enter the task: Submit Project Report
Enter the date for the task (DD/MM/YYYY): 05/08/2025
Task added successfully!
```

---

## 📌 Key Concepts Used

* Object-Oriented Programming (Classes & Static Methods)
* File Handling (`fstream`)
* Date & Time Handling (`ctime`)
* Arrays & Vectors for Task Management
* Switch-Case Menus for Navigation

---

## 🚀 Future Enhancements

* Categorize tasks (Work, Personal, Meetings)
* Task Notifications in real-time
* GUI-based Interface (Qt/Other Frameworks)
* Recurring Task Support
* Save tasks in JSON/Database for structured management

---

## 👩‍💻 Author

**Shreya Jalmi**
\[NIT Goa | GirlScript Summer of Code Contributor]
GitHub: [@SvJalmi](https://github.com/SvJalmi)

---

## 🖇 License

This project is open-source and free for learning purposes. Feel free to fork and modify!






