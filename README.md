#  SQL Database Management System (C++ Backend & JavaFX UI)

A custom SQL-based Database Management System (DBMS) designed to demonstrate advanced **Object-Oriented Programming** principles and **cross-language interoperability**.

##  Project Core Concept
The primary objective was to implement a high-performance database engine in **C++** and seamlessly integrate it into a **JavaFX** desktop application. This was achieved by compiling the C++ logic into a **Dynamic Link Library (DLL)** and consuming it as a native library within the Java environment.

##  Technical Architecture
- **Backend (C++):** - Core DBMS logic and SQL query parsing.
    - Efficient data storage and retrieval mechanisms.
    - Exported as a native **DLL** for Windows.
- **Frontend (JavaFX):** - Modern graphical user interface for database management.
    - Handles user input and displays query results.
- **Integration (JNI / Native Bridge):** - Used Java Native Interface (JNI) to bridge the gap between Java and the C++ backend.
    - Implemented native method wrappers to call C++ functions directly from Java code.

##  Key Features
- **SQL Query Support:** Implementation of standard SQL commands for database manipulation.
- **Native Performance:** Leverages the speed of C++ for heavy-duty data processing.
- **Cross-Language Communication:** Demonstrates the ability to manage memory and data types across the C++ and Java boundary.

##  Academic Context
Developed as a final project for the **Object-Oriented Programming Practicum** at the School of Electrical Engineering (ETF), University of Belgrade.

---
**Author:** Milinko Miletić
