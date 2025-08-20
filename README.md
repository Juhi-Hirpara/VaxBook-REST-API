# 💉 Covid-19 Vaccination Booking REST API  

---

## 📂 **Project Structure**
The project is designed with a **modular architecture** ensuring **scalability, security, and maintainability**.  
It consists of **separate modules for User, Doctor, Admin, Authentication, and Dose Management**.  
Every module is developed following **REST principles** and communicates with the database using **Spring Data JPA & Hibernate**.  

---

## ✨ **Key Functionalities**
- **Secure Authentication** → Session-based login with unique UUID tokens.  
- **Role-Based Access Control** → Different functionalities for **Users, Doctors, and Admins**.  
- **Vaccination Slot Booking** → Citizens can **browse centers and reserve appointments**.  
- **Dose Tracking** → System automatically generates and tracks vaccine doses for every booking.  
- **Data Management** → Admins can **add, update, or remove users, doctors, and centers**.  

---

## 🛠 **Tech Stack**
- ☕ **Java (JDK 17+)**  
- 🌱 **Spring Boot Framework**  
- 🗄️ **Spring Data JPA & Hibernate**  
- 🐬 **MySQL Database**  
- 📦 **Maven Build Tool**  

---

## 📦 **Modules**
- 🔐 **Authentication Module** → Handles user login/logout and session tokens.  
- 🙍 **User Module** → Registration, profile updates, slot booking, and vaccination status.  
- 👨‍⚕️ **Doctor Module** → Appointment handling and vaccination confirmation.  
- 🛡 **Admin Module** → Management of users, doctors, centers, and dose records.  
- 💉 **Dose Module** → Generation and allocation of vaccine doses.  

---

## 🚀 **Features**
### 👥 User Features  
- Register and securely log in.  
- View **vaccination centers near them**.  
- Book **appointment slots**.  
- Update personal profile (only after authentication).  

### 🩺 Doctor Features  
- Access upcoming user appointments.  
- **Mark vaccination completion** for patients.  

### 🛡 Admin Features  
- Full administrative control.  
- Add, update, and delete **Users and Doctors**.  
- Access details of all centers and vaccination data.  
