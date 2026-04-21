# Distributed Systems and Middleware Technologies

A second-hand car advertisement application based on an Erlang distributed server.

## Overview

This repository contains a distributed web-based application designed for managing **users**, **advertisements**, **cars**, and **orders** in a second-hand car marketplace.

The system combines multiple technologies and architectural layers:

- **Angular** for the front-end
- **Spring Boot** for the backend REST API
- **Erlang** for the distributed server component
- **MySQL** for user information
- **Mnesia** for advertisement and order data

The application also uses **JWT-based authentication** and **role-based authorization** to secure access to the system. 
## Main Idea

The goal of the project is to develop a distributed application for second-hand car advertisements by combining middleware technologies with web development and database integration.

The platform is intended to support:

- user management
- car advertisement publishing
- order handling
- secure access control
- distributed processing through an Erlang-based server

The current repository README explicitly describes the system as a second-hand car advertisement application built around an Erlang distributed server. 

## Architecture

The system is composed of the following major components:

- **Front-end** developed with Angular
- **Backend REST API** built with Spring Boot
- **Distributed Erlang server**
- **MySQL database** for user-related data
- **Mnesia database** for advertisement and order-related data

This structure reflects a multi-tier and multi-technology architecture designed for distributed application development. 

## Features

- User management
- Advertisement management
- Car-related operations
- Order management
- Distributed server-based architecture
- REST API integration
- JWT-based authentication
- Role-based authorization

These features are directly aligned with the current repository description shown on GitHub. 

## Tech Stack

- Angular
- Spring Boot
- Erlang
- MySQL
- Mnesia
- JWT Authentication

GitHub currently reports the repository languages as:

- **Java: 80.0%**
- **Erlang: 20.0%** 
## Repository Structure

The repository currently contains the following main files and folders:

```text
.
├── Erlang.api/
│   └── api/
├── Documentation.final.pdf
├── README.md
├── back-end.zip
└── front-end.zip
```

This suggests that the repository includes source material for the distributed Erlang component, a packaged backend, a packaged frontend, and a final project documentation file.

## Security Model

The repository description explicitly states that the system uses:

- **JWT-based authentication**
- **role-based authorization**

This indicates that access to application functionality is controlled according to user identity and permissions.

## Data Management

The application uses two separate databases:

- **MySQL** for storing user information
- **Mnesia** for handling advertisement and order data

This separation reflects the distributed and multi-structured nature of the system design. 

## Documentation

The repository includes:

- `Documentation.final.pdf`

This file likely contains the detailed system design, implementation details, and project explanation. 
## Design Goals

This project was developed with the following goals:

- build a distributed web application
- integrate middleware technologies in a practical scenario
- separate concerns across front-end, backend, and distributed components
- use different databases based on data type and system role
- provide secure access through authentication and authorization mechanisms

## Notes

This project represents a distributed second-hand car advertisement platform built with Angular, Spring Boot, Erlang, MySQL, and Mnesia. It combines web application development with middleware and distributed systems concepts in a single architecture.
## License

This project is licensed under the MIT License.
