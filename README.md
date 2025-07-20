# 🚗 Virtual Parking System

## 📌 Project Overview
The **Virtual Parking System** is a desktop-based application developed using **Java Swing** with a manually coded GUI. It simulates a real-world parking lot environment, allowing users to log in, manage parking slots, view vehicle records, and configure administrative settings such as base payment and total parking capacity. The project is modular, scalable, and later enhanced using **Spring Boot** and **Maven** for enterprise-level deployment.

---

## 🧱 Architecture & Design

### 🔹 Core Modules
| Module             | Description |
|--------------------|-------------|
| `Welcome`          | Main dashboard for navigation between modules. |
| `Login`            | Handles user authentication. |
| `Parking`          | Manages parking operations including slot assignment and fee calculation. |
| `Record`           | Displays parking history and logs. |
| `Admin_Settings`   | Allows admin to view and update base payment and parking capacity. |

Each module is built using object-oriented principles and event-driven programming.

---

## 🛠️ Technologies Used

### 💻 Core Stack
- **Java SE**
- **Swing (GUI)**
- **Event-driven programming**

### 🚀 Enhancements
- **Spring Boot** – for layered architecture (Controller, Service, Repository)
- **Spring Data JPA** – for database integration (MySQL)
- **Spring Security** – for authentication and role-based access
- **Maven** – for dependency management and project structuring
- **JUnit** – for unit and integration testing

---

## 📦 Features

- Modular GUI screens for each functionality
- Manual layout design using Swing components
- Input validation and error handling
- Confirmation dialogs for user actions
- Role-based login system
- Persistent storage using MySQL
- RESTful APIs for scalability (via Spring Boot)
- Automated builds and dependency resolution (via Maven)
- Test coverage using JUnit

---

## 🧪 Testing

- **Unit Tests**: Validate individual methods and logic
- **Integration Tests**: Ensure modules work together correctly
- **Manual UI Testing**: Verify user interactions and navigation

---

## 🧰 Setup Instructions

### 🔹 Java Swing Version
1. Clone the repository.
2. Open in any Java IDE (e.g., IntelliJ IDEA or Eclipse).
3. Compile and run `Welcome.java` to start the application.

### 🔹 Spring Boot Version
1. Ensure Java 17+ and Maven are installed.
2. Clone the repository.
3. Configure `application.properties` with your MySQL credentials.
4. Run `mvn spring-boot:run` to start the application.
5. Access REST endpoints or frontend (if integrated).

---

## 📈 Future Enhancements

- Add vehicle type and duration-based pricing
- Integrate QR code for parking receipts
- Add real-time slot tracking
- Export records to PDF or Excel
- Deploy as a cloud-based microservice
- Add user registration and password recovery

---

## 👨‍💻 Author
**Qureshi** – Full-stack Developer passionate about building scalable and user-friendly systems.

---

## 📄 License
This project is open-source and available under the MIT License.

