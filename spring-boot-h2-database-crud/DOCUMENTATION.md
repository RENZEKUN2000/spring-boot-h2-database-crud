# Project Overview

This project is a Spring Boot application implementing a CRUD system for tutorials using Spring Data JPA with H2 in-memory database. It's designed to demonstrate basic Spring Boot features and REST API development.

## Architecture and Design

- **Framework**: Spring Boot for rapid application development.
- **Database**: H2 in-memory database for storing tutorial data.
- **ORM**: Spring Data JPA for object-relational mapping.
- **API**: RESTful API design to perform CRUD operations on tutorials.

## Installation and Configuration

1. Clone the repository:

## Usage Guide

The application exposes several REST endpoints:

- `GET /api/tutorials`: List all tutorials.
- `POST /api/tutorials`: Create a new tutorial.
- `GET /api/tutorials/{id}`: Retrieve a tutorial by ID.
- `PUT /api/tutorials/{id}`: Update a tutorial.
- `DELETE /api/tutorials/{id}`: Delete a tutorial.
- `GET /api/tutorials/published`: List published tutorials.

## FAQ

- **How to change the database?**
  - The application uses H2 in-memory database. To change, update `application.properties` with new database settings.

## Contributing

Contributions are welcome. Please fork the repository and submit pull requests with any updates or improvements.

## License

This project is licensed under the MIT License.
