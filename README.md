# Spring Boot reCaptcha Validation
This repository contains a Spring Boot application that demonstrates how to validate Google reCaptcha using the reCaptcha API. The application displays a form with a reCaptcha widget and validates the reCaptcha upon form submission.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
Java 8 or higher
Maven
An IDE (such as IntelliJ IDEA)
A Google reCaptcha API key (see below)
###Installing
Clone the repository to your local machine:
git clone https://github.com/abdullahbakis/spring-boot-reCaptcha-validation.git
Import the project into your IDE as a Maven project.

In the application.properties file, enter your Google reCaptcha API key in the google.recaptcha.key property.

Run the project as a Spring Boot application.

Open a web browser and navigate to http://localhost:8080 to access the application.

Complete the reCaptcha widget and submit the form. The application will display a message indicating whether the reCaptcha was validated successfully.
### Obtaining a Google reCaptcha API Key
Go to the Google reCaptcha Admin Console.

Sign in with your Google account.

Fill out the form to register a new site.

In the "Label" field, enter a name for your site (e.g. "Spring Boot reCaptcha Validation App").

In the "reCAPTCHA type" field, select "reCAPTCHA v2".

In the "Domains" field, enter the domain(s) where you will be using the reCaptcha widget. If you are running the application locally, you can use "localhost".

Accept the reCaptcha terms of service and click the "Submit" button.
You will be provided with a site key and a secret key. The site key is used to display the reCaptcha widget on your site, and the secret key is used to validate the reCaptcha on the server side.
# Built With
Spring Boot - The web framework used
Maven - Dependency Management
Spring Boot DevTools - Used for automatic reloading of the application during development
Spring Web - Used for handling HTTP requests and responses
Thymeleaf - Used for rendering HTML templates on the server side
Google reCaptcha API - Used for validating the reCaptcha widget
# Authors
Abdullah Bakış - abdullahbakis
# License
This project is licensed under the MIT License - see the LICENSE file for details.

