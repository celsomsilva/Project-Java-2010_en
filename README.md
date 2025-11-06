
## Technologies Used

![Java](https://img.shields.io/badge/Java%20SE-6%2F7-007396?logo=java&logoColor=white)
![JDBC](https://img.shields.io/badge/JDBC-Database-blue)
![MySQL](https://img.shields.io/badge/MySQL-5.x-4479A1?logo=mysql&logoColor=white)
![JasperReports](https://img.shields.io/badge/JasperReports-iReport%20support-cc2020)
![Eclipse](https://img.shields.io/badge/Eclipse-IDE-2C2255?logo=eclipseide&logoColor=white)
![License](https://img.shields.io/github/license/celsomsilva/project-java-2010)


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
> In 2025(this English version), the structure was aligned to the correct physical package hierarchy.


```
Project-Java-2010_en/
└── src/
    ├── br/
    │   └── com/
    │       └── project/
    │           ├── controller/
    │           │   ├── StudentController.java
    │           │   ├── ScholarController.java
    │           │   ├── ScholarshipController.java
    │           │   └── ProfessorController.java
    │           │
    │           ├── dao/
    │           │   ├── Student.java
    │           │   ├── StudentDAO.java
    │           │   ├── Scholar.java
    │           │   ├── ScholarDAO.java
    │           │   ├── Scholarship.java
    │           │   ├── ScholarshipDAO.java
    │           │   ├── Person.java
    │           │   ├── Professor.java
    │           │   ├── ProfessorDAO.java
    │           │   └── DBConnection.java
    │           │
    │           └── view/
    │               ├── StudentWindow.java
    │               ├── ScholarshipWindow.java
    │               ├── ScholarWindow.java
    │               ├── ProfessorWindow.java
    │               ├── PersonWindow.java
    │               ├── MainWindow.java
    │               ├── WindowFrame.java
    │               ├── MyPanel.java
    │               ├── PanelButtons.java
    │               └── geomatica_background.jpg
    │
    ├── LICENSE
    └── README.md

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



## Licensing

**MIT License**

```
Copyright (c) 2010-2025

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software...
```

---

## Important Notes

- The system heavily relies on **JasperReports/iReport** for reporting — which requires external configuration not present in this repository.
- Original .jrxml and compiled .jasper files were omitted.
- Database creation scripts were excluded for privacy and contractual reasons.
- Historical context: This system prototype was part of internal tooling used at **UERJ's Geomatics PGEC program** for academic and administrative scholarship management.
- Source folders in this legacy project (2005–2010) do not follow the `br/com/...` package structure.
- The compiler automatically generated the correct hierarchy inside `/bin`, as was common in early Java IDEs.



---


## About the Author

I’m a Data Science and Analytics specialist (USP postgraduate) and Computer Engineer (UERJ) with a career spanning from **Pascal/C/Java roots** to **modern Machine Learning and AI**.

My academic and professional background includes:

- **Computation in general**
- **Machine Learning**
- **Hierarchical nonlinear mixed models (HLM3/HLM2)**, **Intraclass correlation (ICC)** and other topics about **HLM**
- **Residual diagnostics and model validation**
- **Deep Learning, LLMs, and Reinforcement Learning (ongoing specialization)**

---

## Contact  

- [LinkedIn](https://linkedin.com/in/celso-m-silva)  
- Or open an [issue](https://github.com/celsomsilva/project-java-2010_en/issues)


