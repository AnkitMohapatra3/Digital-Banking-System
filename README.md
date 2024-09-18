# Online Banking System

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Database Setup](#database-setup)
- [Running the Application](#running-the-application)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
The **Online Banking System** is a secure, web-based platform that provides banking services, such as account management, fund transfers, and transaction history tracking. This system is built using modern web technologies with an emphasis on security, scalability, and ease of use.

## Features
- User authentication (login/logout) using Spring Security
- View account balance and transaction history
- Transfer funds between accounts
- Admin functionalities for managing users and accounts
- Responsive user interface with Bootstrap framework

## Technologies Used
### Frontend:
- **HTML**: Markup language for building the user interface
- **CSS (Bootstrap)**: Styling and responsive layout
- **JavaScript**: Client-side interactivity

### Backend:
- **Java (Spring Boot)**: Backend logic and services
- **JPA (Java Persistence API)**: ORM for database interactions

### Security:
- **Spring Security**: Provides secure authentication and authorization

### Database:
- **MySQL**: Database for storing user and transaction information

## Installation
### Prerequisites
- **Java 17**
- **MySQL**
- **Apache Maven**: For managing project dependencies
- **IDE**: IntelliJ IDEA or Eclipse

### Steps
1. **Clone the repository to your local machine:**
   ```bash
   git clone https://github.com/your-username/online-banking-system.git
   cd online-banking-system
 2.**Install Maven dependencies:**

  `mvn clean install`
  
 3. **Configure your database settings in `application.properties`:**
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/online_banking_db
   spring.datasource.username=root
   spring.datasource.password=password
   spring.jpa.hibernate.ddl-auto=update

### Database Setup

1.**Create a MySQL database:**
   
   `CREATE DATABASE online_banking_db;`

2.The database tables will be automatically created by JPA when the application runs for the first time.

**Running the Application**

To run the application, use the Maven Spring Boot plugin:

`mvn spring-boot:run`

Access the application at http://localhost:8080.

Contributing
Contributions are welcome! Please open an issue or submit a pull request with your improvements.

License
This project is licensed under the MIT License. You are free to use, modify, and distribute this project under the terms of the license.


### Additional Notes:
- The project uses **Spring Boot 3.2.4** as noted in your `pom.xml` file&#8203;:contentReference[oaicite:0]{index=0}.
- Dependencies include essential libraries like `spring-boot-starter-web`, `spring-boot-starter-data-jpa`, `mysql-connector-j`, and others to facilitate web services and database integration.

