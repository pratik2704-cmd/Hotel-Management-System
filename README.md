# 🏨 Hotel Management System (Java)

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![IDE](https://img.shields.io/badge/IDE-Eclipse-blue?style=for-the-badge)
![Database](https://img.shields.io/badge/Database-MySQL-orange?style=for-the-badge)

---

## 📌 Project Overview
The **Hotel Management System** is a desktop-based application developed using **Java (Swing/JavaFX)** and **MySQL**.  
It helps hotel staff manage daily operations like customer details, room booking, employee management, and more.

---

## 🚀 Features

- 🔐 Login System
- 🧑 Add Customer Details
- 🏨 Room Management
- 👨‍💼 Employee Management
- 🚗 Driver Management
- 📊 Dashboard Overview
- 🔍 Search Rooms
- 🧾 Reception Panel

---

## 🛠️ Technologies Used

- ☕ Java (Core Java, Swing/JavaFX)
- 🛢️ MySQL Database
- 🧰 Eclipse IDE
- 🔌 JDBC (Java Database Connectivity)

---

## 📂 Full Project Structure

```
Hotel-Management-System/
│
├── src/
│   └── hotel/management/system/
│       ├── AddCustomer.java
│       ├── AddDriver.java
│       ├── AddEmployee.java
│       ├── AddRooms.java
│       ├── Dashboard.java
│       ├── Login.java
│       ├── Reception.java
│       ├── Room.java
│       ├── SearchRoom.java
│       ├── Conn.java              # Database connection class
│       └── Main.java              # Entry point
│
├── lib/                           # External libraries (JAR files)
│   └── mysql-connector-java.jar
│
├── screenshots/                   # Project output images
│   ├── login.png
│   └── dashboard.png
│
├── database/                      # SQL files (if any)
│   └── hotel_management.sql
│
├── pom.xml                        # Maven config (if used)
├── .classpath                     # Eclipse config
├── .project                       # Eclipse config
├── README.md                      # Project documentation
└── .gitignore                     # Ignore unnecessary files
```

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/hotel-management-system.git
```

### 2️⃣ Open in Eclipse
- Go to **File → Import**
- Select **Existing Projects into Workspace**
- Choose the project folder

### 3️⃣ Setup Database
- Install MySQL
- Create a database (e.g., `hotel_management`)
- Import SQL file (if provided)

### 4️⃣ Configure Database Connection

Update your JDBC code:

```java
Connection con = DriverManager.getConnection(
    "jdbc:mysql://localhost:3306/hotel_management",
    "username",
    "password"
);
```

### 5️⃣ Run the Project
- Open `Main.java`
- Right click → **Run As → Java Application**

---

## 📸 Project Output

### 🔐 Login Screen
![Login UI](./screenshots/login.png)

### 📊 Dashboard
![Dashboard](./screenshots/dashboard.png)

---

## ❗ Common Issues

- ❌ JDBC Driver Missing  
  → Add MySQL connector `.jar` in **Build Path**

- ❌ Database Not Connected  
  → Check username, password, and DB name

- ❌ JavaFX Error  
  → Add VM arguments if using JavaFX

---

## 🙌 Author

**Pratik Kumbhar**  
💻 Java Developer | Web Developer

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
