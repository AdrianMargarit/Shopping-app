# Shopping application using Spring MVC with CRUD principles

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
