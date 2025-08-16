## 📚 Java Library Management System
![Java](https://img.shields.io/badge/Java-8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Project Type](https://img.shields.io/badge/Type-Console%20App-orange)

A simple, menu-driven Library Management System built in Java using switch statements. This project helps learners understand core Java concepts like classes, objects, and control flow while simulating real-world operations such as book tracking and student registration.

---

## 🚀 Why Build This Project?

This mini-project is designed to strengthen your understanding of:

- ✅ Using `switch` statements for menu-driven applications
- ✅ Managing data with classes and objects
- ✅ Implementing real-world features like search, add, update, and borrow
- ✅ Designing modular, readable code across multiple files

---

## 🧠 Features

This Library Management System is designed to simulate core operations of a real-world library. It offers a robust set of features that make it easy to manage books and students efficiently:

### 📘 Book Management

- **➕ Add New Book**  
  Add a new book to the library by entering its serial number, title, author, and quantity.

- **🔁 Update Book Quantity**  
  Increase the number of available copies for an existing book.

- **🔍 Search Book**  
  Search for books by either serial number or author name using a nested switch menu.

- **📚 View All Books**  
  Display a complete list of all books in the library along with their availability status.

- **📤 Check-Out Book**  
  Allow registered students to borrow books, with quantity updates and borrowing limits enforced.

- **📥 Check-In Book**  
  Return borrowed books and update the available quantity in the system.

---

### 🧑‍🎓 Student Management

- **📝 Register Student**  
  Add a new student to the system by entering their name and unique registration number.

- **📋 View Registered Students**  
  Display all students currently registered in the library system.

- **📦 Borrowing Limit Enforcement**  
  Each student can borrow up to 3 books at a time, tracked via an internal array.

- **✅ Borrow/Return Validation**  
  Ensures only registered students can borrow or return books, maintaining data integrity.

---

### 🧭 User Interaction & Control Flow

- **📜 Menu-Driven Interface**  
  Intuitive console-based menu using `switch` statements and `do-while` loops for smooth navigation.

- **🔚 Exit Application**  
  Gracefully terminate the program when the user chooses to exit.

---


## 🗂️ Project Structure

| File Name      | Responsibility                                                                 |
|----------------|----------------------------------------------------------------------------------|
| `Library.java` | Main application with menu and execution flow                                   |
| `book.java`    | Represents individual book details                                               |
| `books.java`   | Manages collection of books and related operations                              |
| `student.java` | Represents individual student details                                            |
| `students.java`| Manages student records and handles book borrowing/returning                    |

> ⚠️ Note: While Java conventionally uses uppercase class names, lowercase is used here for clarity and simplicity.

---

## 🛠️ How It Works

Each class plays a specific role:

- **`book.java`**: Stores book details like serial number, name, author, total and available quantity.
- **`books.java`**: Handles operations like adding books, updating quantity, searching, check-in/check-out.
- **`student.java`**: Stores student details and tracks up to 3 borrowed books.
- **`students.java`**: Manages student registration, ensures uniqueness, and validates borrowing/returning.
- **`Library.java`**: Displays menu, handles user input via `switch`, and coordinates actions across classes.

---

## 🧪 How to Run

1. Clone the repository or copy the files into your Java project.
2. Compile all `.java` files:
   ```bash
   javac Library.java book.java books.java student.java students.java
   ```
3. Run the main class:
   ```bash
   java Library
   ```

---

## 📌 Notes

- Ensure all files are in the same directory for compilation.
- Input is handled via `Scanner`, so run in a terminal or console that supports standard input.
- The system uses basic arrays and control flow—no external libraries required.

---

## 🙌 Contributing

Feel free to fork, improve, or modularize further! Suggestions for enhancements like file-based persistence, GUI integration, or database support are welcome.

---

## 📄 License

This project is open-source and free to use for educational purposes.
