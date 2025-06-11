# 🛒 E-Commerce Product Management API

A simple Spring Boot-based REST API for managing products in an e-commerce system. It allows basic product CRUD operations using PostgreSQL as the database.

---

## 🚀 Features

- Add, Update, Delete, and View Products
- RESTful API using Spring Boot
- PostgreSQL Database Integration
- Basic validation and error handling

---

## 🛠️ Tech Stack

- Java 17
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Maven
- Postman (for testing)

---

## 🧪 How to Run Locally

1. Clone the repository  
   git clone https://github.com/yourusername/ecommerce-springboot.git
   cd ecommerce-springboot
2. Create a PostgreSQL database (e.g., ecommerce_db)

3. Update application.properties:

   properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/ecommerce_db
   spring.datasource.username=your_db_user
   spring.datasource.password=your_db_password
   spring.jpa.hibernate.ddl-auto=update
   
4. Run the project:
   mvn spring-boot:run
