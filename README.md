📦 Inventory Management System 🛒

A desktop-based Inventory Management System built in Java (Swing + JDBC) with MySQL backend — suitable for small to mid-sized shops to manage products, suppliers, users, stock, and transactions.

✅ Features

Product Management (Add, Edit, Delete, Search)

Supplier & Customer Management

User Login & Authentication

Sales & Purchase Tracking

Automatic Stock Updates

Java Swing-based GUI

MySQL Database Integration

💻 Tech Stack

Java (Swing)

JDBC

MySQL

NetBeans / IntelliJ IDEA / Eclipse

1️⃣ Clone the Repository
git clone https://github.com/AshutoshSingh1s/InventoryManagementSystem.git

2️⃣ Import SQL File

Open MySQL Workbench or phpMyAdmin

Click Server → Data Import (or "Import Database")

Select the SQL file from the project folder

Click Start Import

This will create:

Database

Tables

3️⃣ Configure Database Connection

Open the project in your IDE and update your DB credentials.

Default login details:

username: root
password: root


Make sure these match your MySQL setup.

4️⃣ Run the Project

Open the main Java file in your IDE

Press Run

Login using the default credentials (if provided)

📁 Project Structure
InventoryManagementSystem/
│
├── src/                # Java Source Code (GUI + DAO + DB Layer)
├── lib/                # External JAR Libraries
├── SQL/                # Database Schema File (.sql)
└── screenshots/        # (Optional) App UI Screens

🤝 Contribution

Want to improve this project?

Add new features

Fix bugs

Improve UI

Submit pull requests

All contributions are welcome! 🚀

📌 Notes

Ensure MySQL server is running before launching the application

Update database credentials based on your local setup

This is an educational project — feel free to extend it with:

Billing system

Reports

Analytics

Additional modules
