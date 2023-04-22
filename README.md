# user-management-system

* Spring framework and Java language used.

* Data Flow(function are used ...)

  ```
  constructor
  setter and 
  getter etc
  ```

* Package
  ```
  1.model
  2.controller
  3.service
  4.repository
  ```
  
* Data Structure
  > Arrays
  
  > List
  
  > String
  
* Project Summary
  > Step 1: Create a Spring project using Spring Initializer

   Go to the Spring Initializer website (https://start.spring.io/) and select the following options:
  <p>
  Project: Maven
  Language: Java
  Spring Boot: 2.5.0 (or the latest version at the time of your project creation)
  Group: com.example
  Artifact: user-management-system
  Packaging: Jar
  Java: 11 (or the latest version at the time of your project creation)
  Click on the "Add Dependencies" button and search for the following dependencies:
  </p>

  Spring Web
  Spring Data JPA
  H2 Database
  Spring Boot DevTools (optional)
  Click on the "Generate" button and download the generated project as a zip file.

  > Step 2: Create a User model

  Create a new package named "model" inside the "src/main/java/com/example/usermanagementsystem" directory. Inside the "model" package, create a new Java class named   "User" with the following attributes:
  
  > Step 3: Implement all endpoints

  Create a new package named "controller" inside the "src/main/java/com/example/usermanagementsystem" directory. Inside the "controller" package, create a new Java     class named "UserController" with the following endpoints:
  
  > Step 4: Create UserRepository

  Create a new package named "repository" inside the "src/main/java/com/example/usermanagementsystem" directory. Inside the "repository" package, create a new Java     interface named "UserRepository" that extends the JpaRepository interface:
  
  > Step 5: Run the application

  You can now run the application using
