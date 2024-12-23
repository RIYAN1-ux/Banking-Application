
# Banking Application using Java8, Spring Boot, Spring Security, and H2 Database

A RESTful API to simulate simple banking operations, developed using Java 8 and Spring Boot.

## Features

- **Customer Management**: Perform CRUD operations on customers.
- **Account Management**: Handle account creation, updates, and deletion.
- **Transaction Support**:  
  - Deposits and withdrawals.  
  - Internal transfers between accounts.

---

## Getting Started

Follow these steps to set up and run the project:

### 1. Clone the Repository

```bash
git clone https://github.com/RiyanChoudhury/BankApp.git
```

### 2. Enable Lombok Support

Ensure your IDE has Lombok enabled. For setup instructions, refer to the [Lombok Setup Guide](https://projectlombok.org/setup/eclipse).

### 3. Import and Build the Project

1. Open your IDE (e.g., IntelliJ, Eclipse, or Spring Tool Suite).  
2. Import the project as an existing Maven project.
3. Build and run the project:
   ```bash
   mvn clean install
   ```
4. For Spring Tool Suite users, run the application as a "Spring Boot App."

### 4. Default API Port

The application runs on port **8989** by default.

---

## Prerequisites

- **Java 8**  
- **Maven**: For dependency management ([Download Maven](https://maven.apache.org/)).  
- **IDE**: Spring Tool Suite 4 or any Java-supporting IDE.

---

## Key Dependencies

Here’s the list of primary Maven dependencies used in the project:

```text
spring-boot-starter-actuator
spring-boot-starter-data-jpa
spring-boot-starter-security
spring-boot-starter-web
spring-boot-devtools
h2 - In-memory database
lombok - To reduce boilerplate code
springfox-swagger2
springfox-swagger-ui
spring-boot-starter-test
spring-security-test
```

---

## API Documentation (Swagger)

Access the Swagger UI for testing and API exploration:  
[Swagger UI](http://localhost:8989/bank-api/swagger-ui.html)

---

## H2 In-Memory Database

- Default JDBC URL: `jdbc:h2:mem:testdb`
- To customize the database name, update the `application.yml` file.  
- Access the H2 console at: [H2 Console](http://localhost:8989/bank-api/h2-console/)

---

## Testing the API

1. Use the Swagger UI link to perform CRUD operations.
2. Sample JSON requests can be found in the directory:  
   `<project-root>/src/test/resources`

---

## Author

**Riyan Choudhury, Subhraja Sahoo, Abhilipsha Maharana, Prachi Priyadarshini**  

