# C to Java Code Converter GUI Tool

This project is a GUI-based application that allows users to:
- Store C and Java program categories
- View program names
- Convert `.c` files into `.java` files
- Store file paths and data in a database

## 📌 Features

- 🗃️ **Categorized Program List**: A searchable list of stored C/Java programs
- 🔄 **Code Conversion**: Automatically converts C programs into their Java equivalents
- 💾 **Database Integration**: Saves file paths and program metadata into a database
- 🖥️ **GUI Interface**: User-friendly interface to browse, view, and convert files

## 🎯 Project Objectives

- Convert C language `.c` files into Java `.java` files
- Provide a searchable list of stored programs
- Demonstrate Object-Oriented Programming concepts through conversion logic
- Implement exception handling for safe execution and data management

## 🧠 System Overview

C and Java have different programming paradigms (procedural vs. object-oriented). The tool:
- Parses and maps C structures (e.g., loops, functions, array operations) to their Java equivalents
- Uses Java features like:
  - `Scanner` for input
  - `System.out.println()` for output
  - Try-catch blocks for exception handling
  - Recursion and inheritance for advanced features

## 🛠️ Technologies Used

- **Java**: Core programming language
- **Swing/AWT**: GUI components
- **JDBC**: Database connectivity
- **SQL/SQLite/MySQL**: Database management (based on implementation)
- **NetBeans/Eclipse**: (Assumed IDEs used for development)

## 🧪 Examples of Conversion

- **Character case reversal**
- **Loop operations (for, while, do-while)**
- **Array summation with bounds checking**
- **Recursive functions with inheritance**
- **Polymorphism for advanced conversions**

## 🧾 Authors

- Md. Yeasir Arafath Emon (ID: 2020-2-60-182)
- Nowshin Tabassum Ushna (ID: 2020-2-60-083)

## 🧑‍🏫 Supervisor

Md Mostofa Rassel  
Assistant Professor, Dept. of Computer Science and Engineering  
Course: Object-Oriented Programming (CSE110, Sec-01)

## 📁 Project Structure

```
/src
  ├── GUI.java
  ├── Converter.java
  ├── DatabaseManager.java
  └── ...
/resources
  └── sample.c
  └── sample.java
README.md
```

## ✅ How to Run

1. Clone this repository
2. Open the project in your preferred IDE
3. Ensure your Java and JDBC setup is complete
4. Run the GUI main class
5. Use the GUI to browse, convert, and save files

---

> This project demonstrates a practical approach to object-oriented principles by converting procedural C code to Java, highlighting the challenges and adaptations required in real-world programming language transitions.
