# 🧩 REST API – Spring Boot + MySQL + Docker

This is a simple RESTful API built with **Java Spring Boot**, designed to manage products (or any custom entity). It uses **Docker + Docker Compose** to run locally with a MySQL database.

## 🚀 Technologies

- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- MySQL
- Docker & Docker Compose

## 📦 Project Structure

src/
├── main/
│   ├── java/com/enzotoso/api/
│   │   ├── controller/
│   │   ├── model/
│   │   ├── repository/
│   │   └── service/
│   └── resources/
│       ├── application.properties
│       └── ...

## 🐳 How to Run with Docker

Make sure you have Docker and Docker Compose installed.

1. Clone the repository:
   ```bash
   git clone https://github.com/EnzoToso01/Api-rest.git
   cd Api-rest
2. Start the containers:
docker-compose up --build

3. The API will be available at:
http://localhost:8080

Sample Endpoints
GET /products → Get all products
POST /products → Create a new product
GET /products/{id} → Get a product by ID
PUT /products/{id} → Update a product
DELETE /products/{id} → Delete a product

🧪 How to Test
You can use tools like Postman, Insomnia, or curl to test the endpoints.

📁 Environment Variables
If needed, you can define custom variables in a .env file
(you can base it on the provided .env.example).

💡 Why this project?
This project demonstrates how to create a clean, dockerized, database-connected REST API using Java and Spring Boot. It's great for learning purposes, technical interviews, or as a base for bigger applications.
