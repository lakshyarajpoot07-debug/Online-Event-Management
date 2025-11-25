🎉 Online Event Manager System

The Online Event Manager is a desktop-based application built with Java Swing that makes event management simple and efficient. Users can create, modify, remove, and browse events through an intuitive graphical interface. All event records are saved permanently in a MySQL database using JDBC.

📁 Folder Layout
Online-Event-Manager/
│── DBConnection.java
│── EventManagerUI.java
│── Launcher.java
│── schema.sql
│── README.md

📌 File Overview
File	Role
🔹 Launcher.java	Entry file — launches the full application
🔹 EventManagerUI.java	Contains GUI components and program logic
🔹 DBConnection.java	Provides reusable database connectivity using JDBC
🔹 schema.sql	SQL file to create database tables
🔹 README.md	Documentation and project usage instructions

🏆 Functional Highlights

✔ Create and save new events
✔ Edit previously added events
✔ Delete unwanted event records
✔ Display all stored events in a well-formatted table
✔ User-friendly Swing interface
✔ Stores data permanently using MySQL
✔ Includes validation, alerts, and exception handling

🎓 Programming Concepts Used
Concept	Usage
🧠 Object-Oriented Programming	Classes, inheritance, method overriding, and custom exceptions
📚 Collections + Generics	Uses ArrayList<Event> for type-safe data handling
🔄 Multithreading	Keeps UI responsive during database tasks
🗂 Modular Database Class	DBConnection.java handles all database queries
🔌 JDBC	Used for database connectivity and SQL command execution
🛢 CRUD Operations	Insert, update, delete and retrieve operations using PreparedStatement
