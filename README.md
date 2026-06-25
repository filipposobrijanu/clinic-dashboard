<h1 align="center">Medical Appointment Management System</h1>
<h3 align="center">Healthcare Scheduling & Workflow Engine</h3>

<p align="center">
  A comprehensive, multi-tier web application designed to optimize scheduling workflows between patients, medical professionals, and administrators. Built on a <strong>Java EE (Jakarta EE)</strong> architecture, this system ensures reliable relational data persistence for critical healthcare environments.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="License" />
</p>

---

### Core System Modules

* **Patient Workflow:** Implements secure authentication protocols and dynamic search/discovery APIs and enabling patients to filter medical professionals by specialty.
* **Provider Management Engine:** Empowers doctors with a reactive availability management interface, allowing for precise definition of clinical scheduling windows.

---

### Enterprise Technology Stack

**Backend Framework & Spec Implementations**
<p align="left">
  <img src="https://img.shields.io/badge/Java_EE_/_Jakarta_EE-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java EE" />
  <img src="https://img.shields.io/badge/Java_Servlets-ED8B00?style=for-the-badge&logo=java" alt="Java Servlets" />
  <img src="https://img.shields.io/badge/JavaServer_Pages_(JSP)-ED8B00?style=for-the-badge" alt="JSP" />
</p>

**Web Infrastructure & Server Runtimes**
<p align="left">
  <img src="https://img.shields.io/badge/Apache_Tomcat_9+-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black" alt="Tomcat" />
</p>

**Relational Storage & Enterprise Connectivity**
<p align="left">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Java_Database_Connectivity_(JDBC)-4479A1?style=for-the-badge" alt="JDBC" />
</p>

**Client Presentation & Layout Engineering**
<p align="left">
  <img src="https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS" />
</p>

---

### Application Interface Showcase

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

### Enterprise Deployment Guide

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
