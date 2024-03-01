# Student Management System API

This project is a simple RESTful API for managing students using Spring Boot and JPA (Java Persistence API). It allows users to perform CRUD (Create, Read, Update, Delete) operations on student entities.

## Features

- Add a new student
- Retrieve all students
- Retrieve a single student by ID
- Update a student's details
- Delete a student

## Running the Application Locally

1. **Clone the repository** to your local machine:


## Running the Application Locally
Clone the repository to your local machine:
git clone https://github.com/thanveer20/CRUD-with-SQL.git

Navigate to the project directory:
cd CRUD-with-SQL

Build the project using Maven:
mvn clean install

Run the application:
mvn spring-boot:run

The application should now be running on localhost:8080.

## API Endpoints
POST	/api/students	Add a new student
GET	/api/students	Retrieve all students
GET	/api/students/{id}	Retrieve a student by ID
PUT	/api/students/{id}	Update a student's details
DELETE	/api/students/{id}	Delete a student

## Contributing
If you'd like to contribute to the project, please fork the repository and use a feature branch. Pull requests are warmly welcome.
