# E-Commerce Web Application

## Project Overview
This is a scalable e-commerce web application backend built using Java, Spring Boot, and H2 in-memory database. The application provides RESTful APIs to manage products with basic CRUD operations such as adding and retrieving products. The project demonstrates clean code practices, exception handling, OOP concepts, and version control using Git.

## Features
- REST APIs for product management (Add, View all)
- Input validation and exception handling
- Uses Spring Data JPA with H2 database
- Easily extendable for further e-commerce functionalities

## Technologies Used
- Java 17
- Spring Boot 3.1.0
- Spring Data JPA
- H2 Database (in-memory)
- Maven (build and dependencies)
- Git (version control)

## Setup Instructions

1. Clone the repository:

2. Build the project:

3. Run the application:

4. Access APIs (examples):
- GET all products: `http://localhost:8080/products`
- POST new product: `http://localhost:8080/products` with JSON body:
  ```
  {
    "name": "Sample Product",
    "price": 100.0
  }
  ```

5. Optionally, access H2 console for database inspection at `http://localhost:8080/h2-console`  
JDBC URL: `jdbc:h2:mem:testdb` username: `sa` password: *(leave blank)*

## Note
This project serves as a foundational backend demonstrating Java Spring Boot and REST APIs. It can be extended with frontend integration and additional features.

## License
MIT License
