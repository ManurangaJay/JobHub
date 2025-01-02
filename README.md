# JobHub (Web Application)

A comprehensive **backend REST API application** developed with **Spring Boot**, designed to manage job listings, companies, and company reviews. The project features robust CRUD functionalities, containerization with Docker, database integration using H2 and PostgreSQL, and lays the foundation for a **microservices architecture**. Currently, the project is being extended with a frontend interface to provide a seamless user experience.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)

## Overview
This project provides an API for managing:
- **Job Listings**: Add, retrieve, update, and delete job postings.
- **Companies**: Manage company information.
- **Company Reviews**: Enable CRUD operations for reviews of companies.

The application is built with modern backend development practices and is equipped with monitoring and containerization tools for scalable deployment.

## Features
- **CRUD Operations**:
  - Create, read, update, and delete job listings, companies, and reviews.
- **Database Support**:
  - H2 database for testing.
  - PostgreSQL for production.
- **Containerization**:
  - Dockerized services for easy deployment.
- **Monitoring**:
  - Integrated Spring Boot Actuator for health checks and application monitoring.
- **Inter-Service Communication**:
  - Prepares the groundwork for a microservices architecture.
- **Future Frontend Integration**:
  - React.js frontend is under development to provide a user-friendly interface.

## Technologies Used
### Backend:
- **Spring Boot**: Framework for RESTful API development.
- **Spring MVC, JPA**: For routing and data persistence.
- **PostgreSQL**: Database for production use.
- **H2 Database**: For in-memory testing.

### Tools:
- **Docker**: For containerization of the application.
- **Spring Boot Actuator**: For application monitoring.
- **Postman**: For API testing and debugging.

### Future Frontend:
- **React.js**: Ongoing work for frontend integration.
