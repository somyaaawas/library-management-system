
---

# 📚 Library Management System with Embedded MySQL Integration!!



---

## 🔍 Project Overview

This is a **desktop-based Library Management System** developed using **Java Swing** for the user interface and **MySQL** for backend storage. The system aims to automate and simplify daily library operations such as managing books, members, issuing and returning books, and handling fines.

It supports multiple user roles—**Admin**, **Librarian**, and **User**—each with dedicated dashboards and access to role-specific features.

---

## 🎯 Key Features

* 🔐 **Role-Based Authentication**

  * Secure login and personalized dashboards for Admin, Librarian, and User roles.

* 🛠️ **Admin Panel**

  * Manage books and members (add/edit/delete).
  * View reports and manage application settings.

* 📚 **Librarian Panel**

  * Issue and return books.
  * Monitor due dates and overdue fines.
  * Handle book hold (reservation) requests.

* 👤 **User Dashboard**

  * View currently borrowed books.
  * Check and pay fines.
  * Place hold requests on books.
  * Access payment history.

* 💾 **Embedded MySQL Integration**

  * Database operations are embedded directly in Java classes.
  * Eliminates the need for external ORM frameworks.

* 🔄 **Full CRUD Functionality**

  * Perform Create, Read, Update, and Delete operations for both books and members.

* 🖥️ **User-Friendly Interface**

  * Intuitive and responsive GUI built with Java Swing.

---

## 🛠️ Tech Stack

* **Frontend**: Java Swing
* **Backend**: Java
* **Database**: MySQL (embedded integration)
* **IDE**: IntelliJ IDEA / Eclipse (recommended)

---

## 🚀 Getting Started

### ✅ Prerequisites

* Java JDK 8 or higher
* MySQL Server
* MySQL Connector/J (JDBC driver)

### ⚙️ Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/PrajwalSingh-git/library-management-system.git
   cd library-management-system
   ```

2. **Set Up the MySQL Database**

   * Create a database named `library_db`.
   * Import the provided SQL schema (`schema.sql`) to initialize the required tables.

3. **Configure Database Connection**

   * Open the `DatabaseConnection` class.
   * Update the MySQL username, password, and `DB_URL` as per your system configuration.

4. **Run the Application**

   * Compile and run the main Java class (e.g., `Main.java`).
   * Log in using default credentials or create new users via the Admin panel.

---

## 🤝 Contributing

We welcome contributions! If you'd like to enhance features or fix bugs, feel free to open an issue or submit a pull request.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---


