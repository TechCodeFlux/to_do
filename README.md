<img width="1456" height="720" alt="To-Do List Application" src="https://github.com/user-attachments/assets/c6aebfbf-a936-4f19-a554-461cb1504263" />

# 📝 To-Do List Application

A lightweight **command-line To-Do List application** developed in **C** that demonstrates fundamental file handling concepts through a simple task management system. The application provides an interactive menu-driven interface for creating, viewing, and managing a personal to-do list.

---

## 📖 Project Overview

The To-Do List Application is designed as a beginner-friendly project to illustrate the use of **file handling**, **functions**, **conditional statements**, and **menu-driven programming** in C. Tasks are stored in a local text file, allowing users to save and retrieve their to-do items between program executions.

This project serves as a practical introduction to C programming concepts and file input/output (I/O) operations.

---

## ✨ Features

* 📝 Create a new To-Do list
* ➕ Add new tasks
* 📄 View all saved tasks
* 🗑 Delete the entire To-Do list
* 💾 Store tasks using file handling
* 📂 Persistent data storage with text files
* 🔄 Interactive menu-driven interface
* 🚪 Exit the application safely

---

## 📂 Project Structure

```text
kozhukkatta/
└── to-do/
    ├── todo.c        # Main source code
    ├── text.txt      # Task storage file (generated automatically)
    └── README.md     # Project documentation
```

---

## 🛠 Technology Stack

| Category                 | Technology                                                            |
| ------------------------ | --------------------------------------------------------------------- |
| **Programming Language** | C                                                                     |
| **Compiler**             | GCC                                                                   |
| **Storage**              | Text File (`text.txt`)                                                |
| **Concepts Used**        | File Handling, Functions, Loops, Switch Statements, Conditional Logic |
| **Interface**            | Command Line (CLI)                                                    |

---

## ⚙️ Compilation & Execution

### Compile

```bash
gcc todo.c -o todo
```

### Run

**Linux / macOS**

```bash
./todo
```

**Windows**

```bash
todo.exe
```

---

## 📋 Program Workflow

The application follows a simple menu-driven interface:

1. Create a new To-Do list
2. View existing tasks
3. Add new tasks
4. Delete the To-Do list
5. Exit the application

Tasks are entered one at a time and can be terminated using the keyword:

```text
done
```

All tasks are automatically saved to **text.txt** for future access.

---

## 🧠 Concepts Demonstrated

* File Handling (`fopen`, `fclose`, `fprintf`, `fgets`)
* Functions
* Loops
* Switch-Case Statements
* String Manipulation
* User Input Handling
* Command-Line Programming

---

## ⚠️ Current Limitations

* Supports only a single To-Do list
* Stores tasks in a single text file (`text.txt`)
* Individual tasks cannot be edited or deleted
* No task completion status
* Maximum task length is limited

---

## 🚀 Future Enhancements

* ✅ Mark tasks as completed
* ✏️ Edit existing tasks
* 🗑 Delete individual tasks
* 📅 Add due dates and priorities
* 🔍 Search tasks
* 👥 Support multiple users
* 📂 Multiple To-Do lists
* 🎨 GUI version using C/C++ frameworks
* 💾 Database integration

---

## 📚 Learning Objectives

This project demonstrates practical implementation of:

* File Input/Output (I/O)
* Basic Data Persistence
* Menu-Driven Programming
* Procedural Programming in C
* Command-Line Application Development

---

## 👨‍💻 Author

**Pauljo George**

A beginner-friendly C project created to practice file handling and command-line application development.

---

## 📄 License

This project is intended for educational and learning purposes. Feel free to use, modify, and enhance it for your own learning or academic projects.

---

### ⭐ If you found this project useful, consider giving it a star on GitHub!
