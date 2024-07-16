# JavaDemo

This project is a simple RESTful API built with Java Spring for user registration and authentication using JWT (JSON Web Tokens). It uses MongoDB for data storage.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 22
- Gradle
- MongoDB
- Postman

## Start the project
Clone git repository and start the project

## Testing the API with Postman
### Registration
To register a new user, use the following details:
- URL: `http://localhost:8080/register`
- Method `POST`
- Headers: `Content-Type: application/json`
- Body:
    ```
    {
      "username": "demo",
      "email": "demo@test.com",
      "password": "demo"
    }
    ```

### Registration
To register a new user, use the following details:
- URL: `http://localhost:8080/authenticate`
- Method `POST`
- Headers: `Content-Type: application/json`
- Body:
    ```
    {
      "username": "demo",
      "password": "demo"
    }
    ```
