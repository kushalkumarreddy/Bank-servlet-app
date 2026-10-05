# Bank Servlet Application

A simple Bank Management Web Application developed using Java Servlets, JSP, HTML, and Apache Tomcat.

This project demonstrates important Advanced Java Servlet concepts such as ServletContext, ServletConfig, HttpSession, request handling, URL mapping, login/logout, and session-based authentication.

## Technologies Used

- Java
- Java Servlets
- JSP
- HTML
- Apache Tomcat 10.1
- Eclipse IDE

## Features

- Bank login page
- Username and password validation
- Application-wide bank information using ServletContext
- Servlet-specific configuration using ServletConfig
- Session management using HttpSession
- Dashboard after successful login
- Logout functionality
- Unauthorized users are redirected to the login page
- Common header using JSP

## Project Structure

```text
BankApplication
│
├── Java Resources
│   └── src/main/java
│       └── com.bank
│           ├── LoginServlet.java
│           ├── DashboardServlet.java
│           └── LogoutServlet.java
│
└── src/main/webapp
    ├── WEB-INF
    │   └── web.xml
    ├── login.html
    └── header.jsp
