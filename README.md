# 🎓 Student Management REST API

A robust, enterprise-grade RESTful API built with **Java 17** and **Spring Boot 3**, implementing clean **Controller-Service-Repository (Layered Architecture)** design principles and standardized global exception handling.

---

## 🏗️ Architecture

com.bank.studentmanagementapi/
├── controller/        # REST Controller handling HTTP requests & mapping
├── service/           # Service layer holding business logic
├── repository/        # Spring Data JPA Repository interface
├── model/             # JPA Entities representing database schemas
└── exception/         # Custom exception classes & @ControllerAdvice handler

---

## 🛠️ Tech Stack

* **Language:** Java 17 (LTS)
* **Framework:** Spring Boot 3.2.3
* **Data Access:** Spring Data JPA / Hibernate
* **Database:** H2 In-Memory Database
* **Documentation:** OpenAPI 3 / Swagger UI
* **Build Tool:** Maven

---

## 🔌 API Endpoints

| HTTP Method | Endpoint | Description | Status Code |
| :--- | :--- | :--- | :--- |
| `GET` | `/api/v1/students` | Retrieve all students | `200 OK` |
| `GET` | `/api/v1/students/{id}` | Retrieve a student by ID | `200 OK` / `404 Not Found` |
| `POST` | `/api/v1/students` | Create a new student record | `201 Created` |
| `PUT` | `/api/v1/students/{id}` | Update an existing student | `200 OK` / `404 Not Found` |
| `DELETE` | `/api/v1/students/{id}` | Delete a student by ID | `200 OK` / `404 Not Found` |

---

## 🚀 Getting Started

### Prerequisites
* JDK 17
* Maven 3.8+

### Running the Application Locally
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/StudentManagementAPI.git](https://github.com/YOUR_GITHUB_USERNAME/StudentManagementAPI.git)
   cd StudentManagementAPI

### Final Step: Commit & Push to GitHub

Once you save `README.md` with those corrections, run these terminal commands to push the update live:

```bash
git add README.md
git commit -m "docs: finalize professional README documentation"
git push -u origin main