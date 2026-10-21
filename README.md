# Java Practical Experiments & ShopSphere Project

**Author:** Shrejal Shukla

## 📌 About This Repository

This repository contains Java programming practical experiments and a Java-based e-commerce web application called **ShopSphere**. It covers Java GUI development, networking, database connectivity, and web application development.

## 🛠️ Technologies Used

- Java
- Java Swing and AWT
- Java Socket Programming
- Java RMI (Remote Method Invocation)
- JDBC (Java Database Connectivity)
- MySQL
- HTML, CSS, JavaScript
- Java Servlets
- JSP (JavaServer Pages)
- Apache Tomcat
- Apache Maven
- Visual Studio Code

## 📚 Experiments Included

### 1. Student Registration Form using Java GUI

**Description:** A graphical student registration form developed using Java Swing.

**Concepts Covered:**
- JFrame and JPanel
- JLabel and JTextField
- JRadioButton and ButtonGroup
- JComboBox and JTextArea
- JButton and ActionListener
- GUI event handling

**Objective:** To understand GUI development and event handling in Java.

### 2. Java Server-Client Communication

**Description:** A Java application demonstrating communication between a server and a client using socket programming.

**Concepts Covered:**
- ServerSocket and Socket
- Client-server architecture
- Input and output streams
- Network communication

**Objective:** To understand basic network communication using Java.

### 3. Java RMI Experiment

**Description:** Demonstrates Remote Method Invocation, which allows a Java program to invoke methods on a remote object.

**Concepts Covered:**
- Remote interfaces
- Remote object implementation
- RMI Registry
- Client-server communication

**Objective:** To understand distributed application development using Java RMI.

### 4. JDBC Experiment

**Description:** Demonstrates database connectivity between a Java application and a relational database using JDBC.

**Concepts Covered:**
- Database connection
- SQL queries
- Statement and PreparedStatement
- ResultSet
- SQLException handling

**Objective:** To learn how Java applications interact with databases.

### 5. Java Servlet Experiment

**Description:** Demonstrates server-side web application development using Java Servlets.

**Concepts Covered:**
- Servlet lifecycle
- HTTP requests and responses
- GET and POST methods
- Web application deployment
- Apache Tomcat

**Objective:** To understand request processing and dynamic web application development.

### 6. HTML to JSP Experiment

**Description:** Demonstrates the use of HTML and JSP to create web pages for Java web applications.

**Concepts Covered:**
- HTML page structure
- JavaServer Pages (JSP)
- Dynamic web content
- Web server deployment

**Objective:** To understand how JSP can be used in Java web applications.

## 🛒 7. ShopSphere – Java E-Commerce Web Application

**Description:** ShopSphere is a Java-based e-commerce web application designed to provide an online shopping experience.

**Technologies Used:**
- Frontend: HTML, CSS, JavaScript
- Backend: Java Servlets
- Database Connectivity: JDBC
- Database: MySQL
- Web Server: Apache Tomcat
- Build Tool: Apache Maven

**Planned Features:**
- User registration and login
- Product listing and product details
- Shopping cart
- Order management
- Database integration

*Note: Features should be marked as completed only after they have been implemented and tested.*

**Objective:** To apply Java programming, servlet development, JDBC, and database management concepts in a practical web application.

## 💻 Software Requirements

- Java Development Kit (JDK)
- Visual Studio Code
- Java extensions for VS Code
- Apache Maven
- MySQL Server
- Apache Tomcat compatible with the application's Servlet API

## ▶️ How to Run the Experiments

The execution steps depend on each experiment.

**For Java GUI:**
```bash
javac StudentRegistration.java
java StudentRegistration
```

**For Server-Client:**

Compile the server and client classes, start the server first, and then run the client in a separate terminal.

**For Java RMI:**

Compile the interface, implementation, server, and client classes. Start the RMI registry and server according to the project configuration, then run the client.

**For JDBC:**

Configure the database connection and ensure the required database and JDBC driver are available.

**For Servlet and JSP:**

Build or deploy the web application to a compatible Apache Tomcat server and open the configured URL in a browser.

**For ShopSphere:**

```bash
mvn clean package
```

Deploy the generated WAR file to the configured Tomcat server after setting up the database and connection settings.

## 🎯 Learning Outcomes

- Understanding Java programming concepts
- Building graphical user interfaces
- Implementing client-server communication
- Learning remote method invocation
- Connecting Java applications to databases
- Developing server-side web applications
- Integrating frontend, backend, and database technologies

## 🔐 Security

- Do not upload database passwords or private credentials.
- Use prepared statements for database queries.
- Validate user input.
- Exclude compiled files and generated build folders where appropriate.

## 👩‍💻 Author

**Shrejal Shukla**

## 📄 License

This repository is intended for educational and practical learning purposes. Add an appropriate license if you plan to distribute the code under specific terms.
