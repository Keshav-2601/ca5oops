# Database-Driven Client-Server Application

## Overview
This project is a database-driven client-server application designed to manage entities stored in a MySQL database. It incorporates features such as CRUD operations, JSON data exchange, multithreading, and a menu-driven interface. The application follows best practices in software development, including the use of design patterns, unit testing, and version control.

**Author:** Keshav

## Features

### Database Setup:
- MySQL database table creation and population.

### Data Access Layer (DAO):
- DTO implementation.
- DAO interfaces and implementations for CRUD operations.

### Menu System:
- Interactive menu for user interaction.
- Options for CRUD operations and entity display.

### JSON Conversion:
- JsonConverter class for data conversion to JSON format.
- Methods for converting entities and entity lists to JSON strings.

### Unit Testing:
- JUnit tests to ensure functionality and correctness.

### Client-Server Integration:
- Client-side and server-side components.
- Communication protocols using JSON format.
- Multithreading on the server for concurrent client requests.

### Additional Features:
- Possibility to add related tables for enhanced functionality.

## Setup and Usage

### Database Setup:
- Execute mysqlSetup.sql to create and populate the database table.

### Running the Application:
- Run the server application.
- Run the client application.

### Usage:
- Follow the menu prompts to perform CRUD operations.
- Monitor server console for incoming client requests and responses.

## Dependencies
- MySQL
- Java Development Kit (JDK)
- Gson library for JSON parsing

## Version Control
This project utilizes version control with Git. Commits are made regularly to track changes and ensure project integrity.

## Design Patterns
- Singleton pattern for database connection management.
- Factory pattern for DAO instantiation.

## Unit Tests
JUnit tests ensure the correctness of implemented features.

## Programming Principles
DRY (Don't Repeat Yourself) principle followed throughout development.

## Architecture Diagram
This README provides an overview of the project, instructions for setup and usage, details about dependencies, version control usage, design patterns employed, and programming principles followed. It also includes an architecture diagram illustrating the high-level system design.

Please feel free to modify and expand this README as needed for your specific project requirements.
