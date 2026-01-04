# SISBOL – Scholarship Registration System - English Version


> **Note:** This repository contains the English-translated version of the [original Silbol project](https://github.com/celsomsilva/project-java-2010) repository, including file names, variables, methods, and comments.


---

## Project Status

This repository is **work-in-progress**.  

---


## Overview

This repository contains the source code for **SISBOL (Scholarship Registration System)** — a Java desktop application developed in 2010 as part of an project at **UERJ (Rio de Janeiro State University)**, within the **Postgraduate Program in Computer Engineering – Geomatics Concentration Area (PGEC)**.

The system was designed to manage the registration and control of scholarships, students, advisors, and scholarship holders, along with report generation through **JasperReports/iReport** integrated with a **MySQL database**.

---

## Project Objective

Develop a robust, efficient Java desktop application to:
- Register, update, and delete records of students, scholarships, advisors, and scholarship holders.
- Generate and print useful departmental reports using JasperReports.
- Securely manage database access via user login integrated with **MySQL**.

---

## Features

- **User Authentication**
- **CRUD operations** for:
  - Students
  - Advisors
  - Scholarships
  - Scholarship Holders
- **Dynamic Report Generation** using **iReport/JasperReports**
- **Role-based Access Control**
- **Simple and lightweight Swing GUI**

---

## Tech Stack

- Java SE 6/7
- JDBC (Database connectivity)
- MySQL 5.x
- JasperReports / iReport
- Eclipse IDE

---

## Project Structure

> Originally developed in 2010, this project already used full package declarations (e.g., `package br.com.project.controller`),
> but the source files were stored in a simplified directory layout.  
> In 2026(this English version), the structure was aligned to the correct physical package hierarchy.


```
Project-Java-2010_en/
  src/
    main/
      java/
        br/
          com/
            project/
              controller/
                StudentController.java
                ScholarController.java
                ScholarshipController.java
                ProfessorController.java

              dao/
                StudentDAO.java
                ScholarDAO.java
                ScholarshipDAO.java
                ProfessorDAO.java
                DBConnection.java

              model/
                Student.java
                Scholar.java
                Scholarship.java
                Professor.java
                Person.java

              view/
                StudentWindow.java
                ScholarshipWindow.java
                ScholarWindow.java
                ProfessorWindow.java
                PersonWindow.java
                MainWindow.java
                WindowFrame.java
                MyPanel.java
                PanelButtons.java

      resources/
        images/
          geomatica_background.jpg

  README.md
  LICENSE

```



Only the `.java` source files are included in this repository due to project constraints and Jasper/iReport licensing.

To fully use the project:
1. Install **MySQL 5.x**
2. Install **JasperReports/iReport 3.x**
3. Set up the database schema (SQL scripts not included here)
4. Compile `.java` files using `javac`
5. Configure the report paths inside the source code as per your local environment

---

## Usage Instructions

When launching the application:
- A login window prompts for **MySQL username and password**.
- Upon successful authentication:
  - The main system window appears
  - Menus for **File**, **Registration**, **Reports**, and **Help** are enabled.
- Data operations and report generation become accessible via the GUI.


---

## About the Refactoring

This repository focuses on source code preservation and translation rather than execution.  
All refactoring (class, variable, and comment translation) was performed directly in Eclipse IDE.

---


## Important Notes

- The system heavily relies on **JasperReports/iReport** for reporting — which requires external configuration not present in this repository.
- Original .jrxml and compiled .jasper files were omitted.
- Database creation scripts were excluded for privacy and contractual reasons.
- Historical context: This system prototype was part of internal tooling used at **UERJ's Geomatics PGEC program** for academic and administrative scholarship management.
- Source folders in this legacy project (2005–2010) do not follow the `br/com/...` package structure.
- The compiler automatically generated the correct hierarchy inside `/bin`, as was common in early Java IDEs.



---

## Author

This project was developed by an engineer and data scientist with a background in:

* Postgraduate degree in **Data Science and Analytics (USP)**
* Bachelor's degree in **Computer Engineering (UERJ)**
* Special interest in statistical models, interpretability, and applied AI

---


## Contact  

- [LinkedIn](https://linkedin.com/in/celso-m-silva)  
- Or open an [issue](https://github.com/celsomsilva/project-java-2010_en/issues)


