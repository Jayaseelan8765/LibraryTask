# Library Management System

## Requirements
- Java 17
- Maven
- PostgreSQL

## Setup
1. Clone the repository.
2. Create a PostgreSQL database and update the `application.properties` file with your database details.
3. Run the database scripts in `schema.sql` to create tables.
4. Use Maven to build the project: `mvn clean install`.
5. Run the application: `mvn spring-boot:run`.

## API Endpoints
- `POST /api/books` - Create a new book
- `GET /api/books/{id}` - Get a book by ID

## Running Tests
Run `mvn test` to execute unit tests.