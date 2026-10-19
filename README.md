# 🏦 BankApp - CI/CD Pipeline with GitHub Actions

A Java-based banking web application built with Spring Boot, Maven, and MySQL, featuring an automated Continuous Integration and Continuous Deployment (CI/CD) workflow configured using GitHub Actions.

---

## 📌 Project Overview

This repository demonstrates an end-to-end DevOps pipeline for a Spring Boot application. Every push or pull request to the `main` branch automatically triggers a GitHub Actions workflow that compiles, tests, and packages the application using Apache Maven.

### 🛠️ Tech Stack

* **Language:** Java 17
* **Framework:** Spring Boot
* **Build Tool:** Apache Maven (`mvnw` wrapper included)
* **Database:** MySQL
* **CI/CD Platform:** GitHub Actions
* **Containerization Ready:** Dockerfile included

---

## 📁 Repository Structure

```text
.
├── .github/
│   └── workflows/
│       └── cicd.yml             # GitHub Actions CI/CD configuration
├── src/                         # Application source code
│   ├── main/
│   │   ├── java/com/example/bankapp/   # Controllers, Models, Repositories, Services
│   │   └── resources/           # Application properties, templates, SQL scripts
│   └── test/                    # Unit and integration tests
├── Dockerfile                   # Container configuration
├── pom.xml                      # Maven dependencies and build setup
└── README.md                    # Project documentation
