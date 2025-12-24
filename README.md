# Online Library Management System

## Project Overview
The **Online Library Management System** is a web-based platform designed to automate and streamline library operations. It enables **efficient management** of books, members, borrowing transactions, and administrative tasks. The system provides an **intuitive interface** for both librarians (admins) and users, ensuring smooth and effective library operations.

---

## Features

### 🔹 For Admins:
- Manage book inventory (**Add, Edit, Remove books**).
- Maintain and manage **member records**.
- Track and monitor **borrowing & return transactions**.
- Manage **book categories, authors, and publishers**.
- Generate **reports** on books, members, transactions, and late fees.
- Notify users about **book availability, due dates, and fines**.

### 🔹 For Library Members:
- ✅ Register and manage **personal profiles**.
- ✅ Browse and search for **available books**.
- ✅ Borrow and return books with **automated due date tracking**.
- ✅ Submit **book reviews and ratings**.
- ✅ Receive notifications for **due dates and overdue alerts**.
- ✅ View **borrowing history and outstanding fees**.

---

## 🛠 Technologies Used

### **Frontend:**
- 🌐 HTML, CSS, JavaScript
- 🎨 Bootstrap (for responsive UI)

### **Backend:**
- ☕ Java (Servlets & JSP)
- 🚀 Apache Tomcat (Web Server)

### **Database:**
- 🗄️ MySQL (Data storage and management)

### **Additional Libraries & Frameworks:**
- 🔗 JDBC (Java Database Connectivity)

---

## 📥 Installation Guide

### **🔹 Prerequisites:**
1. ✅ **Java Development Kit (JDK)** installed (**Recommended: JDK 11+**).
2. ✅ **Apache Tomcat** web server.
3. ✅ **MySQL** database server.
4. ✅ A modern **web browser**.

### **🔹 Setup Instructions:**
1. **Clone the repository:**
   ```bash
   git clone https://github.com/mkshahi22/online-library-management-system.git
   ```
2. Import the project into your IDE (IntelliJ IDEA, Eclipse, or NetBeans).
3. Configure the MySQL database:
4. Deploy the project on Apache Tomcat.
5. Run the application and access it via a web browser.

---

## 🔄 System Workflow

### 1️⃣ User Registration & Login:
- Users register and receive a unique Member ID (UXXXXXXL for users, AXXXXXX for admins).
- Login page verifies user credentials and redirects based on user role.

### 2️⃣ Book Management (Admin):
- Admins can add, update, or delete books.
- Books are categorized by author, publisher, and genre.

### 3️⃣ Borrowing & Returns:
- Users borrow books with a due date.
- Late returns incur fees, managed through the Fees Management system.

### 4️⃣ Profile Management:
- Users and Admins can update their profile details (email, phone, password).

### 5️⃣ Notifications & Reports:
- Users receive alerts for due dates, overdue books, and new arrivals.
- Admins generate reports on book transactions, fees, and user activity.

---

## 🏗️ System Architecture

### 🛠 Flowchart:
![image](https://github.com/user-attachments/assets/92f57923-a3c6-4d1e-9ffe-3d33ee508951)
![image](https://github.com/user-attachments/assets/92f57923-a3c6-4d1e-9ffe-3d33ee508951)

flowchart TD
    A([START])
    B[User / Admin Login]
    C{Is User Admin?}

    A --> B
    B --> C

    %% Admin Flow
    C -- Yes --> D[Admin Dashboard]
    D --> E[Manage Books]
    D --> F[Manage Users]
    D --> G[View Transaction Logs]

    %% User Flow
    C -- No --> H[User Dashboard]
    H --> I[Search Books]
    H --> J[Borrow Books]
    H --> K[View Borrowed Books & Due Dates]
    H --> L[Return Book / Calculate Fine]
    L --> M[Send Notifications (Reminders)]
    M --> N([END])

---

## 📂 Project Directory Structure
```
Online-Library-Management-System/
├── src/
│   ├── main/
│   │   ├── java/          # Backend logic (Servlets, DAO, Services)
│   │   ├── resources/     # Configuration files
│   │   └── webapp/        # Frontend files (JSP, HTML, CSS, JS)
│
|
│
├── README.md
└── LICENSE
```

---

## 👥 Contributors
- **Mitthu Kumar** - [GitHub](https://github.com/mkshahi22)
- **Chirag Gupta** - [GitHub](https://github.com/CODERXGUPTA)
- **Pritam Kumar** - [GitHub](https://github.com/9508174493)
- **Shashi Kumar** - [GitHub]()

---
## 📸 Screenshots (To Be Added)
✅ Login Page  
![image](https://github.com/user-attachments/assets/09bb0e12-4735-4652-b8de-c6e16be9b668)

✅ Admin Dashboard  
![image](https://github.com/user-attachments/assets/5e4bada0-394d-4735-b050-6c300b9ed74d)

✅ User Dashboard  
![image](https://github.com/user-attachments/assets/0569e24b-4d47-4133-a45f-e2ea6f69d269)

✅ Book Search & Borrowing  
![image](https://github.com/user-attachments/assets/fe89281e-acb5-4ac2-a4a3-4a11485b784a)

✅ Notifications  
![image](https://github.com/user-attachments/assets/67b9856f-1bb7-4018-878b-8961d5726ac1)



---

## 📞 Contact
For queries or suggestions, reach out to:

📛 **Name:** Mitthu Kumar (Project Lead)   
🔗 **GitHub:** [mkshahi22](https://github.com/mkshahi22)

🎉 **Thank you for exploring the Online Library Management System! 😊📚**
