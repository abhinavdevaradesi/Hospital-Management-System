# 🏥 Hospital Management System (Java + JDBC + MySQL)

A simple **Java console-based application** that manages patient records, displays doctor information, and allows booking appointments. Built using **JDBC** to connect with a **MySQL** database, this project simulates core hospital operations in a modular, beginner-friendly setup.

---

## 🚀 Features

- Add new patients
- View all patients
- View list of doctors
- Book doctor appointments
- Menu-driven console interface

---

## 👤 User Roles

- **Receptionist** – Add/View Patients, View Doctors, Book Appointments  
- **Admin** – Add Doctors via MySQL client manually (no UI access)

---

## 🧱 Technologies Used

- Java
- JDBC
- MySQL
- Eclipse (IDE)
- Git + GitHub

---

## 🗃️ Project Structure

JDBCDemo/
├── src/
│ ├── model/
│ │ ├── Doctor.java
│ │ └── Patient.java
│ └── ui/
│ └── HospitalManagementSystem.java
├── README.md
└── Documentation/
└── HospitalManagementSystem_Documentation.docx

yaml
Copy
Edit

---

## 🛠️ How to Run

1. Install MySQL and create a database named `hospital`.
2. Create required tables (`doctors`, `patients`, `appointments`).
3. Update your MySQL credentials inside `HospitalManagementSystem.java`.
4. Open the project in Eclipse.
5. Compile and run `HospitalManagementSystem.java`.
6. Use the menu to interact with the system.

---

## 🧩 Future Enhancements

- GUI using JavaFX or Swing
- Role-based login system
- Doctor availability & scheduling
- Prescription and billing modules
- Email/SMS notification system
- REST API + frontend integration

---

## 👨‍💻 Author

**Name**: D Abhinav  
**Email**: abhinavdevaradesi@gmail.com  
**GitHub**: [abhinavdevaradesi](https://github.com/abhinavdevaradesi)

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
