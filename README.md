<h1 align="center">
  <br>
  Campus Course & Records Manager (CCRM)
  <br>
</h1>

<p align="center">
  <a href="https://github.com/hirakoisdead/Campus-Course-Records-Manager-CCRM">
    <img src="https://img.shields.io/badge/version-1.0-blue.svg" alt="Version">
  </a>
  <a href="https://github.com/hirakoisdead/Campus-Course-Records-Manager-CCRM/issues">
    <img src="https://img.shields.io/github/issues/hirakoisdead/Campus-Course-Records-Manager-CCRM.svg" alt="Issues">
  </a>
  <a href="https://github.com/hirakoisdead/Campus-Course-Records-Manager-CCRM/stargazers">
    <img src="https://img.shields.io/github/stars/hirakoisdead/Campus-Course-Records-Manager-CCRM.svg" alt="Stars">
  </a>
</p>

<p align="center">
  <a href="#Key-Features">Key Features</a> •
  <a href="#Requirements">Requirements</a> •
  <a href="#How-To-Use">Build & Run</a> •
  <a href="#Project-Structure">Project Structure</a> •
  <a href="#Screenshots">Screenshots</a> 
</p>

---

## Key Features

- **In-Memory Datastore** – Manage students, courses, enrollments
- **Import/Export Support** – JSON & CSV data formats
- **CLI Menu System** – Navigate students, courses, enrollments easily
- **Grade Management** - Manage grade for the enrolled students
---

## Requirements
- JDK 17+
- IDE: IntelliJ IDEA / Eclipse
  
## How To Use

Clone this repository, set up dependencies, and run the main file.

```bash
# Clone this repository
git clone https://github.com/hirakoisdead/Campus-Course-Records-Manager-CCRM.git

# Go into the project directory
cd Campus-Course-Records-Manager-CCRM

# Go into the cli directory
cd CCRM/src/edu/ccrm/cli

# Compile the program
javac Main.java

# Run the program
java Main.java
```

## 📂 Project Structure (detailed)
```

```

---

## 🕰 Evolution of Java
- **1995**: Java 1.0 – Write once, run anywhere
- **1998**: Java 2 (J2SE, J2EE, J2ME introduced)
- **2004**: Java 5 (Generics, Annotations, Enums)
- **2011**: Java 7 (NIO.2, try-with-resources)
- **2014**: Java 8 (Streams, Lambdas, Optional, Date/Time API)
- **2017**: Java 9 (Modules)
- **2019–2025**: Java 11, 17, 21 LTS – modern APIs, Records, Sealed Classes

---

## ☕ Java ME vs SE vs EE
| Edition | Purpose | Example Use Cases |
|---------|---------|------------------|
| **ME (Micro Edition)** | Lightweight, resource-constrained devices | Embedded systems, feature phones |
| **SE (Standard Edition)** | Core Java libraries + APIs | Desktop apps, CLI apps (like CCRM) |
| **EE (Enterprise Edition)** | Adds web, enterprise APIs | Servlets, JSP, Jakarta EE, enterprise backends |

---

## 🔑 JDK, JRE, JVM Explained
- **JVM** (Java Virtual Machine): Executes compiled bytecode.
- **JRE** (Java Runtime Environment): JVM + standard libraries to *run* Java apps.
- **JDK** (Java Development Kit): JRE + compiler + dev tools to *build* apps.

---
## 📑 Mapping Syllabus → Implementation
| Syllabus Topic | Where in Project |
|----------------|------------------|
| OOP (Encapsulation, Inheritance, Polymorphism) | `domain/Student.java`, `domain/Instructor.java`, `domain/Course.java` |
| Abstraction (interfaces) | `service/StudentService.java`, `CourseService.java` |
| Packages | `edu.ccrm.domain`, `edu.ccrm.service`, etc. |
| Exception Handling | `exception/DuplicateEnrollmentException.java` |
| Collections Framework | `DataStore` uses `ConcurrentHashMap`, `List`, `Set` |
| Generics | Service methods with generics (`List<Student>`) |
| I/O (File, NIO.2) | `FileUtil` |
| Threads/Concurrency | `ConcurrentHashMap` in `DataStore` |
| Date/Time API | `Enrollment.java` uses `LocalDate` |
| Assertions | `Person.java` constructor (`assert id > 0`) |

---

# Install on Windows
1. Download **JDK 17** from [Oracle](https://www.oracle.com/java/technologies/downloads/).
2. Install and set environment variables:
    - `JAVA_HOME=C:\Program Files\Java\jdk-17`
    - Add `%JAVA_HOME%\bin` to `PATH`
3. Verify:
   ```
   java -version
   javac -version
   ```
4. Install **Eclipse IDE** 
5. Import project

---

##  Usage (Quick Guide)
![project-set-up.png](resources/project-set-up.png)
---
## 🖥 Screen Shots
# 1. java installation verification
![java-verification.png]()

# 2. project set up and run ( run the commands as described above)
![project-set-up.png]()



# 4. project folders structure
![project-folders-structure.png]()
---
