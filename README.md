
# Admin Dashboard Java

## Overview
This is a **Spring Boot-based Admin Dashboard** that allows for the management of users, roles, and permissions. It uses **Spring Security** for authentication and authorization, providing a secure platform for managing backend functionalities.

## Features
- **User Management**: Create, update, delete users.
- **Role Management**: Assign roles to users.
- **Permission Management**: Define and assign permissions to roles.
- **Security**: Role-based access control (RBAC) using Spring Security.

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/admin-dashboard-java.git
   ```
2. **Set up the database**:
   - Create a MySQL database named `admin_dashboard`.
   - Configure the database connection in the `application.properties` file.
3. **Run the application**:
   - Navigate to the project directory and run the Spring Boot application:
     ```bash
     mvn spring-boot:run
     ```
4. **Test the API**:
   - Use Postman or any other API testing tool to interact with the endpoints.

## API Endpoints

- `GET /api/users`: Retrieve all users.
- `POST /api/users`: Create a new user.
- `DELETE /api/users/{id}`: Delete a user.
- `GET /api/roles`: Retrieve all roles.
- `POST /api/roles`: Create a new role.
- `DELETE /api/roles/{id}`: Delete a role.
