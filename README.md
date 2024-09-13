# Garage Management System Backend

## Overview
This is the backend component of the Garage Management System, built with Spring Boot. It provides RESTful API endpoints for managing garage operations.
## Technologies Used
- Java 21
- Spring Boot 3
- Spring Data JPA
- MySQL Database
- Maven 

## Setup Instructions

### Prerequisites
- Java Development Kit (JDK) 11 or higher
- MySQL 5.7 or higher
- Maven 3.6 or higher

### Steps
1. Clone the repository:
   ```
   git clone https://github.com/Arzgui/garageBack.git
   cd garageBack
   ```

2. Configure the database:
   - Create a MySQL database named `garage_management`
   - Update `src/main/resources/application.properties` with your database credentials:
     ```
     spring.datasource.url=jdbc:mysql://localhost:3306/garage_management
     spring.datasource.username=your_username
     spring.datasource.password=your_password
     ```

3. Build the project:
   ```
   mvn clean install
   ```

4. Run the application:
   ```
   mvn spring-boot:run
   ```

The server will start on `http://localhost:8080`.



