# CloudShare

CloudShare is a full-stack cloud storage platform that enables users to securely upload, organize, search, and share files and folders.

The application uses JWT-based authentication, role-based access control, PostgreSQL for metadata storage, Redis for caching, and Cloudinary for cloud file storage.

## Features

- User registration and login
- JWT-based authentication and authorization
- Role-based access control
- File upload, download, and deletion
- Folder creation, renaming, and deletion
- Nested folder support
- File and folder sharing
- Search files and folders
- Cloudinary integration for file storage
- Redis caching
- RESTful APIs
- Swagger/OpenAPI documentation

## Tech Stack

### Backend

- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- JWT
- PostgreSQL
- Redis
- Cloudinary
- Maven

### Documentation

- Swagger / OpenAPI

## Project Structure

```text
CloudShare
├── src
│   ├── controller
│   ├── service
│   ├── repository
│   ├── entity
│   ├── dto
│   ├── security
│   ├── config
│   ├── exception
│   └── util
├── pom.xml
└── README.md
