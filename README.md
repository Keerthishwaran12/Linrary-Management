📚 Library Management System

A comprehensive Java-based desktop application designed to streamline library operations. This system automates the management of books, members, and circulation records, replacing manual registers with an efficient digital solution.

🚀 Project Overview

Course: CGB1201 – Java Programming

Author: Keerthishwaran A

Register No: 927624BAD045

Department: Artificial Intelligence and Data Science

The Library Management System is built using Java AWT (Abstract Window Toolkit) and Object-Oriented Programming (OOP) principles. It features a user-friendly Dashboard that allows librarians to track inventory, register members, and handle the issue and return of books with automatic fine calculation.

✨ Key Features

1. 🔐 Login Module

Secure entry point for administrators.

Default Credentials:

Username: admin

Password: 123

2. 📖 Book Management

Add new books to the catalog (ID, Title, Author, Quantity).

View real-time stock availability.

Prevents data duplication.

3. 👥 Member Management

Register distinct member types (Student, Faculty).

Store Member IDs and names securely in the system memory.

4. 🔄 Issue & Return System

Issue: Validates stock and member existence before issuing. Automatically decreases stock count.

Return: Updates inventory instantly upon return.

5. 💰 Fine Management

Automatically calculates fines for overdue books.

Logic: ₹2.00 per day for every day past the 7-day borrowing limit.

6. 📊 Reports & Search

Dashboard view for "Current Book Stock" and "Registered Members".

Dynamic text-area updates for easy auditing.

🛠️ Technology Stack

Language: Java (JDK 8+)

GUI: Java AWT (Abstract Window Toolkit) & Swing

Data Structure: Java Collections Framework (ArrayList)

IDE: Eclipse / IntelliJ IDEA / VS Code

⚙️ Installation & Usage

Clone the Repository

git clone [https://github.com/your-username/library-management-system.git](https://github.com/your-username/library-management-system.git)


Navigate to the Directory

cd library-management-system


Compile the Code

javac LibrarySystem.java


Run the Application

java LibrarySystem


🔮 Future Enhancements

[ ] Integration with MySQL database for permanent storage.

[ ] Barcode scanner integration for quick book issue.

[ ] Email notifications for overdue books.

[ ] Student portal for reserving books online.

Developed by Keerthishwaran A
