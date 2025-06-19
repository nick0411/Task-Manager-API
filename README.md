# 📝 Task Manager API

A simple RESTful API for managing tasks (to-dos), built with Spring Boot and Spring Data JPA. for learning backend development, CRUD operations, and REST architecture.

---

## 🚀 Features

* Create, Read, Update, Delete (CRUD) tasks
* Filter tasks by completion status (optional)
* Uses in-memory H2 database (easy to run)
* REST API tested with Postman

---

## ⚙️ Tech Stack

* Java 17+
* Spring Boot
* Spring Web
* Spring Data JPA
* H2 Database
* Lombok (optional)

---

## 📦 Project Structure

```
com.example.Task_Manager_API
├── controller    # REST controllers
├── service       # Business logic
├── repository    # JPA repositories
├── model         # Entity classes
├── dto           # Data transfer objects (optional)
└── TaskManagerApplication.java
```

---

## 🔧 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/nick0411/Task-Manager-API
cd Task-Manager-API
```

### 2. Run the Application

Make sure you have Java and Maven installed.

```bash
./mvnw spring-boot:run
```

### 3. Access the H2 Console (Optional)

* URL: [http://localhost:8080/h2-console](http://localhost:8080/h2-console)
* JDBC URL: `jdbc:h2:mem:testdb`
* User: `sa`
* Password: *(leave blank)*

---

## 🌐 API Endpoints

| Method | Endpoint          | Description       |
| ------ | ----------------- | ----------------- |
| GET    | `/api/tasks`      | Get all tasks     |
| POST   | `/api/tasks`      | Create a new task |
| PUT    | `/api/tasks/{id}` | Update a task     |
| DELETE | `/api/tasks/{id}` | Delete a task     |

> Use Postman or curl to test the endpoints.

---

## 🧪 Future Improvements

* ✅ Add validation
* 🔐 Add user authentication (Spring Security + JWT)
* 🧪 Write unit and integration tests
* 🗃️ Migrate to PostgreSQL or MySQL
* ☁️ Deploy to Render/Fly.io

---

## 🧑‍💻 Author

Nick
[GitHub](https://github.com/nick0411)

---

## 📄 License

This project is licensed under the MIT License.
