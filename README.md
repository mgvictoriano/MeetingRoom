# Meeting Room API

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7.4-brightgreen)
![H2 Database](https://img.shields.io/badge/H2%20Database-In--Memory-orange)
![Java](https://img.shields.io/badge/Java-17-blue)

The "Meeting Room API" is a project developed using Spring Boot, a Java-based development framework designed to simplify web application creation. This API was created to manage meeting rooms, providing an efficient and practical system for scheduling and booking meeting spaces.

## Features

- **Room Creation:** Register new meeting rooms, providing details such as name, date, start time, and end time.

- **Room Listing:** View all available meeting rooms.

- **Room Details:** Retrieve detailed information about a specific room based on its ID.

- **Room Update:** Make changes to the details of an existing meeting room.

- **Room Deletion:** Remove a meeting room from the database.

## Technologies Used

This project utilizes the following technologies:

- **Spring Boot:** A Java development framework that simplifies web application creation.

- **H2 Database:** An in-memory database for storing meeting room information.

- **Java 17:** The primary programming language used for application development.

- **Lombok:** A library that simplifies the creation of Java classes, reducing boilerplate code.

- **Jakarta Validation:** For input data validation.

## Environment Setup

To run this application in your local environment, ensure that you have Java 17 installed. Additionally, this project uses Maven as a dependency management system.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Authors](#authors)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Java 17
- Maven 3
- An IDE for Java development (e.g., IntelliJ IDEA or Eclipse)
- A web browser
- Angular CLI (for the frontend)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/saladereuniao.git
```
2. Open the project in your preferred IDE.

3. Build the project:
```bash
mvn clean install
``` 

Start the Spring Boot application.

## Usage

The API is accessible at http://localhost:8082/api/v1/.
To get a list of all meeting rooms, send a GET request to /rooms.
To get the details of a specific room, send a GET request to /rooms/{id}.
To create a new room, send a POST request to /rooms.
To update a room, send a PUT request to /rooms/{id}.
To delete a room, send a DELETE request to /rooms/{id}.

## Authors
Michelle Gaia Victoriano
