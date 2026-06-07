# Medical Appointment Management System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

A comprehensive enterprise-grade web application designed to streamline appointment scheduling between patients, doctors, and administrators. Built with a robust Java EE architecture, this system ensures reliable data management and secure user interactions for healthcare workflows.

![Medical System Dashboard](Images/1.PNG)

## ✨ Core Features

### 👤 Patient Module
*   **Secure Authentication:** User registration and login functionality.
*   **Search & Discovery:** Search for medical professionals by specialty.
*   **Scheduling Engine:** Book, view, and manage appointments with built-in business logic (e.g., 3-day cancellation policy).

### 🩺 Doctor Module
*   **Availability Management:** Doctors can set and update their own scheduling windows.
*   **Dashboard Views:** Filterable schedule views by day or week to manage patient flow.

### 🛠️ Admin Module
*   **User Management:** Centralized registration and oversight of medical professionals and system records.

## 🛠️ Built With

<p align="left">
  <img src="https://img.shields.io/badge/Java_EE-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java EE" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=for-the-badge&logo=apache-tomcat&logoColor=black" alt="Tomcat" />
  <img src="https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
</p>

![Screenshots Montage](Images/13.PNG)

## 🚀 Getting Started

1. **Prerequisites:**
   * Install [Apache Tomcat](https://tomcat.apache.org/) and a MySQL server.
   * Ensure [Java JDK](https://www.oracle.com/java/technologies/downloads/) is configured.
2. **Setup Database:**
   * Execute the provided SQL scripts in your MySQL environment to initialize the schema.
3. **Deploy:**
   * Clone the repo and import the project into your IDE (Eclipse/IntelliJ).
   * Configure the database credentials in the JDBC connection class.
   * Deploy the WAR file to your Tomcat `/webapps` directory.

## 🤝 Contributing

Contributions are welcome! If you would like to improve the scheduling logic or UI, please fork the repository and submit a pull request.

## 📫 Contact

[obrizanou@gmail.com](mailto:obrizanou@gmail.com)

Project Link: [https://github.com/filipposobrijanu/Medical-Appointment-Management-System](https://github.com/filipposobrijanu/Medical-Appointment-Management-System)
