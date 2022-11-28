# Shopping application using Spring MVC with CRUD principles

![eShop-1](https://user-images.githubusercontent.com/96662075/204269970-c414aa5d-a3f4-4fac-a4c1-db6abef6e526.jpg)

![eShop-2](https://user-images.githubusercontent.com/96662075/204269973-2c087bec-f09f-4115-a856-128b430df069.jpg)

![eShop-3](https://user-images.githubusercontent.com/96662075/204269977-7293cf78-be63-4eb3-bd84-37dff71a9942.jpg)

![eShop-4](https://user-images.githubusercontent.com/96662075/204269978-4b1166c7-864a-4219-b489-3006d79abb38.jpg)

![eShop-5](https://user-images.githubusercontent.com/96662075/204269981-662d77f1-c54e-4f58-b1c9-3d591a36ae71.jpg)

![eShop-6](https://user-images.githubusercontent.com/96662075/204269982-a45bcd4a-4a2b-4061-a037-bfdd1255cbae.jpg)

![eShop-7](https://user-images.githubusercontent.com/96662075/204269984-75b74c11-be14-423d-9d89-04a0119326eb.jpg)

![eShop-8](https://user-images.githubusercontent.com/96662075/204269985-fcaf2517-0ca9-4467-9576-e36409e8805e.jpg)

![eShop-9](https://user-images.githubusercontent.com/96662075/204269986-e2f582fa-618e-43a2-af31-92e286a4d4b4.jpg)

![eShop-10](https://user-images.githubusercontent.com/96662075/204269987-de0d3da4-f70b-427a-8870-19a7b1cbf8ef.jpg)

![eShop-11](https://user-images.githubusercontent.com/96662075/204269988-c0162513-2cde-4405-8e73-1505f9106908.jpg)

![eShop-12](https://user-images.githubusercontent.com/96662075/204269989-052d55bc-470a-4723-ba69-77c48de29cc5.jpg)

![eShop-13](https://user-images.githubusercontent.com/96662075/204269992-b20766f5-831b-4399-b698-c303d2e4c7fd.jpg)

![eShop-14](https://user-images.githubusercontent.com/96662075/204269994-3b5d391f-73d6-453c-b671-d7771053fefa.jpg)

![eShop-15](https://user-images.githubusercontent.com/96662075/204269996-ed3c6d3f-8b25-428e-baee-91abcde6275e.jpg)

![eShop-16](https://user-images.githubusercontent.com/96662075/204269998-a9c73c97-1667-4abb-8939-f8b4874f7d78.jpg)

![eShop-17](https://user-images.githubusercontent.com/96662075/204269999-921c732a-2b96-411e-9078-3696a95e3879.jpg)

![eShop-18](https://user-images.githubusercontent.com/96662075/204270000-89a1e08c-e24d-47f3-b3d0-7aed51ad993b.jpg)

![eShop-19](https://user-images.githubusercontent.com/96662075/204270004-06645e4e-6227-4da6-9d77-ce49d81c8dfa.jpg)

![eShop-20](https://user-images.githubusercontent.com/96662075/204270005-ebd59637-7d01-4a2d-8535-641618efd213.jpg)

# Description

This is a project of a Shopping Web Application in which I have granted several roles for its users. In developing it I had used Spring MVC with CRUD principles. 

# User roles:

## Visitor:

- It is the most basic role that a person can have;
- Browses the application without being logged in;
- Has the capacity to view,search or filter through products;
- Has the capacity to add desired products to the shopping cart;

## Customer:

- Has all the attributes a Visitor can have;
- The Customer has the capacity to place and view its orders;
- Has the capacity to update its Profile Information;

## Employee:

- Has the capacity to view, search or filter through products;
- Doesn't have access to the shopping cart;
- Has the capacity to add, modify or delete products;
- Has the capacity to view all orders at any given time;
- Has the capacity to update its Profile Information;

## Admin:

- Has all the attributes an Employee can have;
- Has the authority to create or delete Employee accounts;
- Has the capacity to view the activity of all Employees;
- Has the capacity to add or delete Categories;

## Technologies used in creating this project:

- Main programming language: Java;
- Front-end: HTML, CSS, JavaScript, AJAXa and Bootstrap;
- Server-side: JSP and JSTL;
- Database: SQL;
- Dependency injection: Spring Core;
- Building the Model-View-Controller application: Spring MVC;
- Database communications and operations: Spring Data JDBC;
- User authentication and authorization: Spring Security;
- Containing the application: Docker;

# Install:

## Requirements:

- Docker;

## Installing the application:

$ git clone https://github.com/AdrianMargarit/Shopping-app.git

$ cd Shopping-app/install

$ docker compose -f app-compose.yaml up

## Executing the application:

The application can be accessed at http://localhost:8888, after all the containers have started.

## Defaults:

By default the application has demo data and role-based accounts:

### Customers:

customer_1.demo@yahoo.com

customer_2.demo@gmail.com

### Employees:

employee_1.demo@yahoo.com

employee_2.demo@gmail.com

### Admin:

admin.demo@gmail.com

### Password is 123456 for every account.

## Stopping the application:

### NOTE: In order to use the following command, you have to be sure you are in the correct directory: Shopping-app/install

$ docker compose -f app-compose.yaml down
