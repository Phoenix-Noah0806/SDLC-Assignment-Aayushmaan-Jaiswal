# Smart-Attend Mobile Application  
**SDLC & DevOps Fundamentals – Assignment**

## Project Overview

This repository contains my assignment for the **SDLC & DevOps Fundamentals course**, based on the roleplay scenario of acting as a **Junior Project Manager / Release Manager** for a university startup project.

The project focuses on the development of **Smart-Attend**, a mobile application designed to automate student attendance using **geo-fencing technology**.

Geo-fencing allows the application to detect when a student enters a predefined geographical boundary around the classroom. When the student is within the specified radius, the system automatically records their attendance.

During the development process, a new requirement was introduced by the university administration: the system must integrate **biometric Face ID verification** to prevent proxy attendance. This requirement was introduced midway through development, creating challenges for the development team.

This assignment analyzes how such requirement changes affect software development when using traditional models like **Waterfall**, and how the **Agile Scrum framework** provides a more flexible and efficient approach.

---

## Assignment Objectives

The objective of this assignment is to demonstrate understanding of key concepts from the **Software Development Life Cycle (SDLC)** and **DevOps practices**, including:

- Analysis of the limitations of the **Waterfall model**
- Understanding how **Agile Scrum handles changing requirements**
- Planning development using **sprints**
- Creating a **Sprint Backlog**
- Explaining the role of **CI/CD (Continuous Integration and Continuous Deployment)** in modern software development

---

## Waterfall Model Failure Analysis

The traditional Waterfall development model follows a **linear sequence of phases**, where each stage must be completed before the next begins.

While this model works well when requirements are stable, it struggles when new requirements appear during development.

In the Smart-Attend project, the addition of **Face ID biometric verification** introduces several challenges:

- **Rigidity of development phases** – Returning to earlier stages like requirements and design becomes difficult.
- **High cost of change** – Adding biometric authentication requires redesigning system components.
- **Delayed testing** – Integration issues between geo-fencing and biometric verification may only appear late in the development cycle.

These limitations demonstrate why Waterfall is not ideal for projects with evolving requirements.

---

## Agile Scrum Approach

To address these challenges, the development team adopts the **Agile Scrum framework**, which supports iterative development and continuous improvement.

Instead of completing the entire system in one long cycle, Agile divides development into short iterations called **sprints**.

Each sprint typically lasts **two weeks** and focuses on delivering a small, functional part of the product.

For the Smart-Attend project, development is organized into two main sprints:

### Sprint 1 – Minimum Viable Product (MVP)

Sprint 1 focuses on building the core functionality of the application.

Features developed in this sprint include:

- Basic mobile application user interface  
- Student login using university credentials  
- Geo-fencing attendance detection  
- Attendance notification system  
- Instructor dashboard for monitoring attendance  

The goal of this sprint is to deliver a **working prototype of the attendance system**.

---

### Sprint 2 – Feature Enhancement

Sprint 2 focuses on improving the system and integrating the newly introduced requirement.

Features implemented in this sprint include:

- **Biometric Face ID verification**
- Improvements to the reporting dashboard
- Security enhancements
- Bug fixes and performance improvements

This iterative development approach allows the team to incorporate changes without restarting the entire project.

---

## Sprint Backlog

A **Sprint Backlog** is a list of tasks that the development team commits to completing during a sprint.

Each task is written as a **user story**, which describes the functionality from the user's perspective.

Example tasks included in the Sprint 1 backlog:

- Student login using university credentials
- Geo-fencing attendance detection
- Real-time teacher dashboard
- Attendance notification system
- Admin override functionality

The Sprint Backlog is provided in the repository as a **CSV spreadsheet**.

---

## CI/CD in the Smart-Attend Project

Modern software development relies heavily on **DevOps practices** to improve efficiency and reliability. One of the most important DevOps practices is **CI/CD (Continuous Integration and Continuous Deployment).**

### Continuous Integration (CI)

Continuous Integration ensures that developers frequently merge their code into a shared repository. Each integration automatically triggers builds and automated tests, helping identify issues early in the development process.

Benefits include:

- Early detection of bugs
- Improved code quality
- Better collaboration among developers

---

### Continuous Deployment (CD)

Continuous Deployment automates the process of releasing new versions of the application to users.

After code passes all automated tests, it can be automatically deployed to production or distribution platforms.

In the Smart-Attend project, CI/CD would allow the development team to quickly release updates such as:

- Integration of Face ID verification
- Improvements to the attendance dashboard
- Bug fixes and performance enhancements

This ensures that users receive new features and improvements quickly and reliably.

---

## Repository Structure

```
SDLC-Assignment-YourName
│
├── Analysis.pdf
├── Sprint_Backlog.csv
└── README.md
```

- **Analysis.pdf** – Detailed report analyzing Waterfall limitations and Agile Scrum implementation  
- **Sprint_Backlog.csv** – Spreadsheet containing tasks planned for Sprint 1  
- **README.md** – Project documentation and explanation of CI/CD usage

---

## Key Concepts Covered

This assignment demonstrates the following SDLC and DevOps concepts:

- Software Development Life Cycle (SDLC)
- Waterfall Development Model
- Agile Methodology
- Scrum Framework
- Sprint Planning
- Sprint Backlog
- DevOps Practices
- Continuous Integration (CI)
- Continuous Deployment (CD)

---

## Conclusion

The Smart-Attend project highlights the challenges of managing changing requirements in software development.

While the Waterfall model provides structure, it lacks flexibility when new requirements emerge during development. The Agile Scrum framework offers a more adaptable solution by dividing development into iterative sprints and allowing continuous improvements.

By combining Agile development with DevOps practices such as CI/CD, development teams can deliver reliable software updates quickly while maintaining high system quality.