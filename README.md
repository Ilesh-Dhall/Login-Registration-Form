# 🛠️ Login & Registration Forms - Java & MySQL

## 📌 Overview
This is a **Java-based Login & Registration Form** project built using **NetBeans**. The project serves as a **front-end interface** for user authentication while storing records securely in a **MySQL database**. It intelligently detects **invalid login attempts** and **prevents unregistered users** from accessing the system using pop-up alerts.

## 🎯 Features
✅ **User Registration**: New users can register with valid credentials.  
✅ **Secure Login**: Authenticates users by checking credentials against a MySQL database.  
✅ **Smart Detection**: Prevents login for unregistered users with alerts.  
✅ **Interactive UI**: Built using Java Swing with **NetBeans form builder**.  
✅ **MySQL Integration**: Stores and retrieves user data securely.  

## 🏗️ Project Structure
```
📦 Login & Registration Forms
├── 📂 Assets
│   └── (Screenshots For README)
├── 📂 build
│   ├── 📂 classes
│   │   ├── Login.class (+ inner classes)
│   │   ├── MyConnection.class
│   │   ├── Registration.class (+ inner classes)
│   │   ├── Login.form
│   │   └── Registration.form
├── 📂 nbproject
│   ├── 📂 private
│   │   └── (NetBeans project files)
├── 📂 src
│   ├── Login.java
│   ├── Login.form
│   ├── MyConnection.java
│   ├── Registration.java
│   └── Registration.form
├── build.xml
├── manifest.mf
└── README.md
```

## ⚙️ Installation & Setup
### 1️⃣ Prerequisites  
- **Java Development Kit (JDK) 8+**  
- **NetBeans IDE** (Recommended for editing `.form` files)  
- **MySQL Server**  

### 2️⃣ Clone the Repository  
```sh
git clone https://github.com/Ilesh-Dhall/Login-Registration-Form.git
cd Login-Registration-Form
```

### 3️⃣ Database Setup
1. Open MySQL Workbench or use the MySQL CLI.
2. Create a database and table using the following SQL:
```
CREATE DATABASE IF NOT EXISTS user_auth;
USE user_auth;

CREATE TABLE Reg_Form (
    First_Name   VARCHAR(20),
    Last_Name    VARCHAR(20),
    Date_of_Birth DATE,
    City         VARCHAR(20),
    Mother_Name  VARCHAR(20),
    Father_Name  VARCHAR(20),
    Class        VARCHAR(4),
    Gender       VARCHAR(10),
    Email        VARCHAR(30),
    Password     VARCHAR(30)
);
```
3. Update MyConnection.java with your database credentials.

## 🖼️ Screenshots
<table align="center">
  <tr>
    <td align="center">
      <img src="Login & Registration Forms/Assets/RegistrationUI.png" alt="Registration Screen" height="250">
      <br><b>Figure 1: Registration Screen</b>
    </td>
    <td align="center">
      <img src="Login & Registration Forms/Assets/LoginUI.png" alt="Login Screen" height="250">
      <br><b>Figure 2: Login Screen</b>
    </td>
  </tr>
</table>

<table align="center">
  <tr>
    <td align="center">
      <img src="Login & Registration Forms/Assets/DatabaseStructure.png" alt="Registration Screen" height="250">
      <br><b>Figure 3: Database Structure</b>
    </td>
    <td align="center">
      <img src="Login & Registration Forms/Assets/DatabaseRecords.png" alt="Login Screen" height="250">
      <br><b>Figure 4: Sample Database Records</b>
    </td>
  </tr>
</table>




## 🚀 Applications  
This Java-based Login & Registration System can be used in various real-world applications, including:  

1️⃣ **College & University Portals** – Used for student registrations, login authentication, and record management.  
2️⃣ **Corporate Employee Management** – Secure login and data storage for employees.  
3️⃣ **E-Commerce & Online Services** – User account creation and authentication in web applications.  
4️⃣ **Event Management Systems** – Register participants and maintain user databases.  
5️⃣ **Secure Web Forms** – Can be extended to web-based login systems using Java Servlets or Spring Boot.  

**Happy Coding :)**
