EchoChat Application
Overview
EchoChat is a simple chat application built using Spring Boot, WebSocket API, HTML, JSP, CSS, and JavaScript. The application allows multiple users to communicate in real-time through a web interface.

Features
Real-time messaging using WebSocket.
Simple and intuitive user interface.
Multi-user chat support.
Technologies Used
Spring Boot: Backend framework for building the application.
WebSocket API: For real-time communication between the server and clients.
HTML/JSP: For structuring the web pages.
CSS: For styling the application.
JavaScript: For client-side scripting and WebSocket handling.
Prerequisites
Java 8 or higher
Maven
A modern web browser (Chrome, Firefox, Edge, etc.)
Project Structure
css
echochat/
│
├── src/main/java/com/example/echochat
│   ├── config
│   │   └── WebSocketConfig.java
│   ├── controller
│   │   └── ChatController.java
│   ├── model
│   │   └── Message.java
│   └── EchoChatApplication.java
│
├── src/main/resources
│   ├── static
│   │   ├── css
│   │   │   └── styles.css
│   │   ├── js
│   │   │   └── chat.js
│   ├── templates
│   │   └── chat.jsp
│   └── application.properties
│
├── src/test/java/com/example/echochat
│
├── pom.xml
│
└── README.md

Authors
Your Name - Saurabh Kumar Pandey
Acknowledgements
Special thanks to all the open-source contributors whose libraries and tools were used in this project.
