# Spring Framework Project – Task 1 

## Project Overview

In this project, I developed **two Java applications using the Spring Framework**. The main goal of this work was to understand how Spring Boot applications are created, how they run locally, and how they handle requests coming from a web browser or API tools such as Postman and Swagger.

The project is divided into two parts:
- **Task 1** focuses on the basics of Spring Boot and simple web interaction.

---

## Task 1 – Basic Spring Boot Web Application

In Task 1, I created a Spring Boot application from scratch and ran it locally.  
After starting the application, it is accessible in a web browser using:

This confirms that the application is running correctly and acting as a local web server.

---

### Greeting Function (Basic Response)

The first functionality I implemented was a **simple greeting response**.

When I open the localhost address in the browser, the application returns a greeting message.  
This step helped me understand how a Spring controller handles an HTTP request and sends a response back to the browser.

The main purpose of this feature was:
- To verify that the application runs correctly
- To understand basic request–response behavior in Spring

![Basic Greeting](src/main/resources/static/screenshots/BasicHello.png)
---

### Greeting Page with HTML View

Next, I extended the application to return an **HTML page instead of plain text**.

At this stage:
- The backend returns a view (HTML file)
- The page displays a greeting message
- An image is also included on the page

This helped me understand how Spring connects backend logic with frontend views and introduced me to the basic idea of the MVC (Model–View–Controller) pattern.

---

### Changing the Name in the Greeting

One of the key features in Task 1 is the ability to **change the name displayed in the greeting**.

How it works conceptually:
- I pass a name through the browser request
- The application reads this value
- The greeting message updates dynamically to include the provided name

For example, instead of a static message, the page can display a personalized greeting such as “Hello, Akmal”.

This feature demonstrates:
- How user input can be handled by the application
- How dynamic content is generated instead of fixed text

---