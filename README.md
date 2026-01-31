## 🧑‍💼 Employee Management System (Java)

- A desktop-based Employee Management System developed using Java (Swing & AWT) that helps organizations manage employee records efficiently.
- The application provides features to add, view, update, and remove employees, along with a secure login system and database connectivity.

---

## 📌 Features

- 🔐 Login Authentication
- ➕ Add New Employee
- 📋 View Employee Details
- ✏️ Update Employee Information
- ❌ Remove Employee
- 🖥️ User-Friendly GUI (Java Swing)
- 🗄️ Database Connectivity using JDBC
- 🚀 Fast and lightweight desktop application

---

## 🛠️ Technologies Used

- Java Core (programming language)
- Swing & AWT (GUI development)
- JDBC (Database connectivity)
- MySQL (Backend database)
- NetBeans (IDE Development environment)

---

## 📂 Project Structure

```text
Employee-Management-System
│
├── src/
│   ├── employee/
│   │   └── management/
│   │       └── system/
│   │           ├── Splash.java
│   │           ├── Login.java
│   │           ├── Home.java
│   │           ├── AddEmployee.java
│   │           ├── ViewEmployee.java
│   │           ├── UpdateEmployee.java
│   │           ├── RemoveEmployee.java
│   │           └── Conn.java
│
├── icons/
│   ├── add_employee.jpg
│   ├── delete.png
│   ├── view.jpg
│   └── home.jpg
│
├── nbproject/
├── build/
├── manifest.mf
└── build.xml
```

---

## 🧩 Module Description

- Splash.java –-> Application startup screen
- Login.java –-> User authentication
- Home.java –-> Dashboard with navigation options
- AddEmployee.java –-> Add new employee records
- ViewEmployee.java -–> Display employee details
- UpdateEmployee.java –-> Modify existing employee data
- RemoveEmployee.java –-> Delete employee records
- Conn.java –-> JDBC connection with MySQL database

---

## 🗄️ Database Details

###  Database Name: employeemanagementsystem
- Sample Table Structure
```text
Sql
CREATE TABLE employee (
    empId INT PRIMARY KEY,
    name VARCHAR(50),
    fatherName VARCHAR(50),
    dob DATE,
    salary VARCHAR(20),
    address VARCHAR(100),
    phone VARCHAR(15),
    email VARCHAR(50),
    education VARCHAR(20),
    designation VARCHAR(30),
    aadhar VARCHAR(20)
);
```
-⚠️ Update database username & password inside Conn.java

---

## ▶️ How to Run the Project (NetBeans)

- 1. Download or clone the repository
- 2. Open NetBeans IDE
- 3. Click File → Open Project
- 4. Select the Employee-Management-System folder
- 5. Configure MySQL database
- 6. Run Splash.java or Login.java

---

## 📸 Appication Screenshots 

- ### Start Page
<img width="600" height="400" alt="Screenshot 2026-01-31 162216" src="https://github.com/user-attachments/assets/69752da0-2cd3-4740-8857-75ffd287b309" />
<br> <br>

- ### 🔐 Login Page
<img width="600" height="400" alt="Screenshot 2026-01-31 162246" src="https://github.com/user-attachments/assets/eb1ecc75-f8f3-4e84-8554-90953ef9f3ac" />
<br> <br>

- ### 🏠 Home Dashboard
<img width="600" height="400" alt="Screenshot 2026-01-31 162310" src="https://github.com/user-attachments/assets/a37ce412-dbfe-47f6-a324-0c745dd44a1b" />
<br> <br>

- ### ➕ Add Employee Page
<img width="600" height="400" alt="Screenshot 2026-01-31 162344" src="https://github.com/user-attachments/assets/a7bbd7b6-f411-4f33-b8dd-2d814364aa97" />
<br> <br>

- ### ✏️ Update Employee Information
<img width="600" height="400" alt="Screenshot 2026-01-31 162408" src="https://github.com/user-attachments/assets/76be84dd-d5e1-424b-b1be-f17d0a215e64" />
<br> <br>

- ### 📋 View Employee Details
<img width="600" height="400" alt="Screenshot 2026-01-31 162408" src="https://github.com/user-attachments/assets/0f3185a1-9b50-46a7-ac6b-4373a90c07f5" />
<br> <br>

- ### ✏️ Print Employee Information Service
<img width="600" height="400" alt="Screenshot 2026-01-31 162441" src="https://github.com/user-attachments/assets/f76865b9-44cd-4e1d-b06e-0dbf0e36588e" />
<br> <br>

- ### ❌ Remove Employee Page
<img width="600" height="400" alt="Screenshot 2026-01-31 162500" src="https://github.com/user-attachments/assets/14224c33-de95-487d-93bc-c4b71c8d16e5" />
<br> <br>

---

## 🎯 Use Cases

- Small & medium organizations
- College mini-project
- Java Swing practice project
- Interview portfolio project

---

## 🚀 Future Enhancements

- Role-based authentication (Admin/User)
- Search & filter employees
- Export data to PDF/Excel
- Password encryption
- Modern UI (JavaFX)

---

## 👨‍💻 Author :- Tushar Patil

- 🎓 Computer Engineering Graduate
- 💻 Java | SQL | Data Structures | OOP

---

## Don’t forget to star ⭐ the repository and share your feedback!
