# Library Book Management API

A simple Spring Boot RESTful API for managing library books. This project is for educational purposes and demonstrates basic REST controller usage with sample data.

## Features
- List all books
- Get a book by ID
- Search books by title
- Add a new book
- Delete a book by ID

## Technologies
- Java 21
- Spring Boot
- Maven

## Project Structure
- `controller.library` - REST controllers
- `model.library` - Data models

## How to Run
1. Open the project in your IDE.
2. Build with Maven: `mvn clean install`
3. Run the application: `mvn spring-boot:run`
4. Test endpoints using Postman or browser at `http://localhost:8080/api/books`

## Endpoints
- `GET /api/books` - List all books
- `GET /api/books/{id}` - Get book by ID
- `GET /api/books/search?title={title}` - Search books by title
- `POST /api/books` - Add a new book
- `DELETE /api/books/{id}` - Delete a book by ID

## Note
- No service or repository layers are used. All logic and sample data are in the controller.
