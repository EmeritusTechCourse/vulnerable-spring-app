# Security in Spring Boot
This repository contains a project with a number of vulnerabilities that you will need to fix.

## Thymeleaf
This project uses a Java templating library called "Thymeleaf". We do not cover this in this course, but it should be easy for you to understand. You can see an overview of everything you need to know using this resource https://www.thymeleaf.org/doc/tutorials/3.0/usingthymeleaf.html#using-thtext-and-externalizing-text. 


Pick 2 vulnerabilities and fix them. 

## XSS
We're able to send arbitrary blocks of text and HTML markup to the server and render them. Explore the thymeleaf docs to understand how this is happening and find a fix
## SQL Injection
It's possible to extend one of the requests so that we can perform dangerous queries against the database
## Identification and Authentication failures
The authentication is flawed and it is not using password hashing
## Security logging and monitoring failures
We do not log any of the key user events
## Cryptographic Failure
We're using out of date and/or flawed cryptography strategies
