SkillHub Backend

Overview

SkillHub Backend is a Java-based backend system designed to manage assessments, micro-credentials, achievements, discussions, projects, and personalized learning recommendations. It provides a structured API for user interactions, scoring assessments, awarding credentials, and facilitating collaboration.

Tech Stack

Language: Java

Framework: Spring Boot

Database: PostgreSQL

Authentication: JWT (JSON Web Token)

ORM: Hibernate

API Documentation: Swagger

Build Tool: Maven/Gradle

Features

1. User Management

Registration & Authentication (JWT-based)

Role-based access control (Admin, User, Evaluator, etc.)

2. Assessments & Evaluations

Support for Hard & Soft skill assessments

Dynamic question bank

AI-based evaluation for answers

Scoring system with detailed reports

3. Micro-Credentials & Achievements

Automated awarding of micro-credentials based on assessment performance

User achievements for gamification

Rank system based on accumulated points

4. Peer Learning & Collaboration

Discussion forums with threaded posts

Project-based collaboration with team roles

5. Personalized Learning

Learning resource recommendations based on assessment performance

Installation & Setup

Prerequisites

Java 17+

PostgreSQL

Maven or Gradle

Steps

Clone the repository:

git clone https://github.com/your-repo/skillhub-backend.git
cd skillhub-backend

Configure database settings in application.properties:

spring.datasource.url=jdbc:postgresql://localhost:5432/skillhub
spring.datasource.username=your_username
spring.datasource.password=your_password

Build and run the project:

mvn spring-boot:run

or using Gradle:

./gradlew bootRun

API will be available at http://localhost:8080

API Documentation

Swagger UI available at:

http://localhost:8080/swagger-ui.html

Contributing

Fork the repository

Create a new branch (feature/your-feature)

Commit changes

Open a pull request

License

This project is licensed under the MIT License.