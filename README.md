<h1 align="center">Medical Appointment Management System</h1>
<h3 align="center">Enterprise-Grade Healthcare Scheduling & Workflow Engine</h3>

<p align="center">
  A comprehensive, multi-tier enterprise web application designed to optimize scheduling workflows between patients, medical professionals, and administrators. Built on a robust <strong>Java EE (Jakarta EE)</strong> architecture, this system ensures reliable relational data persistence, strict authorization patterns, and high-performance throughput for critical healthcare environments.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="License" />
</p>

---

### ✨ Core System Modules

* **Patient Workflow:** Implements secure authentication protocols and dynamic search/discovery APIs, enabling patients to filter medical professionals by specialty and execute complex scheduling workflows subject to strict business-logic constraints (e.g., automated cancellation windows).
* **Provider Management Engine:** Empowers doctors with a reactive availability-management interface, allowing for precise definition of clinical scheduling windows and filtered daily/weekly patient-flow views.
* **Admin Orchestration Layer:** Centralized governance for stakeholder lifecycle management, providing full oversight of professional registries, appointment audit logs, and system data integrity.

---

### 🛠️ Enterprise Technology Stack

**Backend & Business Logic**
<p align="left">
  <img src="https://img.shields.io/badge/Java_EE-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java EE" />
  <img src="https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=for-the-badge&logo=apache-tomcat&logoColor=black" alt="Tomcat" />
</p>

**Data Persistence & Frontend Presentation**
<p align="left">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
</p>

---

### 📸 Application Interface Showcase

<p align="center">
  <img src="Images/1.PNG" width="48%" />
  <img src="Images/13.PNG" width="48%" />
</p>
<p align="center">
  <img src="Images/6.PNG" width="48%" />
  <img src="Images/2.PNG" width="48%" />
</p>
<p align="center">
  <img src="Images/3.PNG" width="48%" />
  <img src="Images/4.PNG" width="48%" />
</p>
<p align="center">
  <img src="Images/5.PNG" width="48%" />
  <img src="Images/8.PNG" width="48%" />
</p>
<p align="center">
  <img src="Images/7.PNG" width="48%" />
  <img src="Images/9.PNG" width="48%" />
</p>

---

### 🚀 Enterprise Deployment Guide

**1. Infrastructure Prerequisites:**
* **Java JDK:** Ensure a production-compatible JDK (11+) is configured in your environment.
* **Server Runtime:** Install **Apache Tomcat** as your servlet container.
* **Database Engine:** Ensure a **MySQL** server instance is running.

**2. Database Initialization:**
* Execute the provided `.sql` migration scripts within your MySQL instance to seed the schema and necessary constraints.

**3. Application Deployment:**
* Clone the repository and import the workspace into an IDE (IntelliJ IDEA or Eclipse).
* Configure the `JDBC` data-source credentials within the project's connectivity configuration class.
* Compile the project into a `.war` file and deploy directly to the `webapps` folder in your Tomcat home directory.

---

### 🤝 Contribution & Contact

Contributions are highly encouraged, particularly concerning the optimization of scheduling algorithms or the enhancement of UI accessibility. Please fork the repository and submit a formal pull request.

**Inquiries:** [obrizanou@gmail.com](mailto:obrizanou@gmail.com)
