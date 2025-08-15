# 🏥 Hospital & Appointment Management System  

An intuitive and efficient web-based application 💻 that streamlines hospital operations 🩺 by managing doctors 👨‍⚕️, patients 🧑‍🤝‍🧑, specialists 👩‍⚕️, and appointments 📅 through role-based access 🔐 and seamless online workflows.  

---

## ✨ Features

- **🛠️ Admin Dashboard**  
  - ➕ Add, ✏️ edit, and 🗑️ delete doctors  
  - 📋 Manage specialists  
  - 📊 View counts of total doctors, patients, specialists, and appointments  

- **👨‍⚕️ Doctor Panel**  
  - 🔐 Secure login  
  - 📅 View appointments and update their statuses  

- **🧑‍🤝‍🧑 Patient Panel**  
  - 📝 Register and login  
  - 📅 Book, view, and cancel appointments  
  - ✅ Receive appointment confirmation  

- **🗄️ Database Integration**  
  - 💾 MySQL-based backend  
  - 📌 Handles tables: `doctor`, `patient` (user_details), `specialist`, `appointment`  
  - 📅 Proper handling of `DATE` and unique constraints  

- **🎨 Responsive UI**  
  - 🖥️ Built with Servlets & JSP for server-side logic  
  - 📱 Clean, modern, and mobile-friendly interface  

---

## 🛠️ Technologies Used

| Layer          | Technologies & Tools           |
|----------------|--------------------------------|
| Backend        | ☕ Java (Servlets, JSP)         |
| Database       | 🗄️ MySQL                        |
| Frontend       | 🌐 HTML, 🎨 CSS, 🎯 Bootstrap, ⚡ JavaScript |
| Session & Auth | 🔐 HttpSession, role-based checks |
| Tools          | 🐙 Git, 📦 Maven/Gradle (optional)   |

---

## 🚀 Installation & Setup

1. **📥 Clone the repository**  
   ```bash
   git clone https://github.com/Swetha-S-2410/Hospital-and-Appointment-Management-System.git

## 🗄️ Database Setup

🏗️ **Create the hospital database** in MySQL.  
▶️ Run the provided SQL script to generate tables (`doctor`, `user_details`, `specialist`, `appointment`).

---

## ⚙️ Configure Database Credentials

✏️ Update connection parameters in **DBConnection.java**.

---

## 📦 Deploy to Server

🏗️ Build your project (**Maven/Gradle**).  
🌐 Deploy WAR to **Apache Tomcat**.  
🔗 Access via: `http://localhost:8080/<context>/admin/doctor.jsp`.

---

## ✅ Run and Test

👨‍💼 **Log in as Admin** → manage doctors/specialists.  
🧑‍🤝‍🧑 **Sign up as Patient** → book appointments.  
👨‍⚕️ **Log in as Doctor** → manage appointments.

---
## 📂 Project Structure

```plaintext
Hospital-and-Appointment-Management-System/
├── src/
│   ├── com.hms.db/             # Database connection util
│   ├── com.hms.dao/            # DAO classes (DoctorDAO, AppointmentDAO)
│   ├── com.hms.entity/         # Entity classes (Doctor, Appointment, etc.)
│   └── com.hms.admin.servlet/  # Admin Servlets
├── WebContent/
│   ├── admin/                  # Admin JSP pages
│   ├── component/              # Common includes (navbar, CSS)
│   ├── doctor/                 # Doctor panel
│   ├── patient/                # Patient panel
│   └── admin_login.jsp         # Login page
└── README.md                   # This documentation
```


---

## 🖼️ Screenshot Preview

## 🖼️ Screenshot Gallery

### 📌 Admin Dashboard
<p align="center">
  <img src="images/Screenshot 2025-08-12 205733.png" alt="Admin Dashboard" width="600">
  <img src="images/Screenshot 2025-08-12 205844.png" alt="Dashboard" width="300">
  <img src="images/Screenshot 2025-08-12 210215.png" alt="ADMIN lOGIN" width="300">
  <img src="images/Screenshot 2025-08-12 210314.png" alt="Dashboard" width="300">
  <img src="images/Screenshot 2025-08-12 210356.png" alt="ADD DOCTOR" width="300">
  <img src="images/Screenshot 2025-08-12 210421.png" alt="LIST OF DOCTORS" width="300">
</p>

### 📌 Doctor Login
<p align="center">
  <img src="images/Screenshot 2025-08-12 210519.png" alt="Doctor Login" width="600">
  <img src="images/Screenshot 2025-08-12 210647.png" alt="DOCTOR DASHBOARD" width="600">
  <img src="images/Screenshot 2025-08-12 210716.png" alt="Patient Details" width="600">
  <img src="images/Screenshot 2025-08-12 210807.png" alt="Edit Doctor" width="600">
</p>

### 📌 USER APPOINTMENT
<p align="center">
  <img src="images/Screenshot 2025-08-12 210920.png" alt="User Appointment" width="600">
</p>

### 📌 User Login
<p align="center">
  <img src="images/Screenshot 2025-08-12 211003.png" alt="User Login" width="600">
  <img src="images/Screenshot 2025-08-12 211223.png" alt="User Register" width="600">
  <img src="images/Screenshot 2025-08-12 211308.png" alt="Appointment List" width="600">
</p>
---

## 📊 UML & ER Diagrams

🗺️ **ER Diagram**: Shows entities and relationships (doctors, patients, specialists, appointments).  
📐 **UML Diagrams**: Class and Use Case diagrams generated with PlantUML.  

### 📌 ER DIAGRAM
<p align="center">
  <img src="images/er.jpg" alt="ER DIAGRAM" width="600">
</p>

### 📌 USECASE DIAGRAM
<p align="center">
  <img src="images/use.jpg" alt="USECASE DIAGRAM" width="600">
</p>

### 📌 CLASS DIAGRAM
<p align="center">
  <img src="images/class.jpg" alt="USECASE DIAGRAM" width="600">
</p>


---

## 🔮 Future Enhancements

📧 Email/SMS Notifications for booking confirmations  
🛡️ Advanced role-based access control (RBAC)  
🗓️ Doctor availability & slot booking  
📈 Reports & Analytics for admin  

---

## 👩‍💻 About

Developed under the name **MediTrack** 🏥 — a complete web-based solution to digitalize hospital workflows and enhance operational efficiency 🚀.

---

## 📬 Contact

💌 For queries, feedback, or contributions: **[SWETHA/ swethaesc24@gmail.com]**

