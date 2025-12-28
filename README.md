# CapstonProject

This capstone project is a full-stack, microservices-based application designed using Spring Boot, REST APIs, service discovery, and a modern frontend UI. The system follows a cloud-native architecture and demonstrates real-world concepts such as service-to-service communication, API Gateway routing, user management, and scalable backend design.

The project focuses on clean separation of concerns, scalability, and maintainability using microservices principles.

🏗️ System Architecture

The application is built using a microservices architecture with the following components:

Eureka Server – Service discovery and registration

API Gateway – Centralized routing, request handling, and security entry point

User Service – Handles user registration, authentication, and profile management

Player List Service – Manages player/content listings

Favorite Service – Allows users to manage favorite items

Admin Service – Administrative operations and system management

Frontend UI – User-facing interface for interacting with backend services

Each service is independently deployable and communicates via RESTful APIs.

🧩 Microservices Breakdown
🔹 Eureka Server

Acts as the service registry

Enables dynamic service discovery

Eliminates hardcoded service URLs

🔹 API Gateway

Routes requests to appropriate microservices

Acts as a single entry point for the system

Simplifies client-to-service communication

🔹 User Service

Handles user authentication and authorization

Manages user data and profiles

Exposes REST APIs for frontend integration

🔹 Player List Service

Manages core application data

Provides APIs to retrieve and manage player/content information

🔹 Favorite Service

Allows users to add/remove favorite items

Maintains user-specific preferences

🔹 Admin Service

Handles administrative features

Manages system-level operations

🔹 Frontend (CplayerUI)

Built to interact with backend APIs

Provides a clean and responsive user interface

Consumes API Gateway endpoints

🛠️ Tech Stack
Backend

Java

Spring Boot

Spring Cloud

RESTful APIs

Eureka Server

API Gateway

Frontend

HTML

CSS

JavaScript

(UI integrated with backend services)

Database

Relational database (service-specific data persistence)

Tools & Concepts

Microservices Architecture

Service Discovery

API Gateway Pattern

Layered Architecture

SDLC & REST principles

🚀 Key Features

Microservices-based system design

Independent service deployment

Centralized API Gateway routing

Service discovery using Eureka

Scalable and modular backend services

Clean separation between frontend and backend
