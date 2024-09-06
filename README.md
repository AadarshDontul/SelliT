**Sellit Application**

Project Overview
The Sellit Application is a Spring Boot-based web application designed to facilate Inter University college students to Sell thier used items and buy items from other students even if they belong to different college . It uses Java 17, Spring Boot 2.7.7, Hibernate, and PostgreSQL for its backend services.

Features
User Management: Premium user can post and non-premimum can just see post by other and can buy.
Data Persistence: Integrated with PostgreSQL for data storage.
Authentication : User login is required for Authencity.

*Prerequisites*
Before you begin, ensure you have met the following requirements:

Java 17: [Download and install from the official Oracle website or OpenJDK]
Maven: [Download and install Maven from https://maven.apache.org/download.cgi]
PostgreSQL: [Download and install from https://www.postgresql.org/download/]
IDE (Optional): [Recommended IDEs like IntelliJ IDEA or Eclipse]

*Installation and Setup*
Clone the Repository

bash
Copy code
git clone https://github.com/your-username/sellit.git
cd sellit
Configure Database

Make sure PostgreSQL is running.

Create a database for the application.

Update the database configuration in src/main/resources/application.properties or src/main/resources/application.yml:

properties
Copy code
spring.datasource.url=jdbc:postgresql://localhost:5432/your_database_name
spring.datasource.username=your_username
spring.datasource.password=your_password
Build the Application

Use Maven to build the project:

bash
Copy code
mvn clean install
Run the Application

You can run the application from the command line:

bash
Copy code
mvn spring-boot:run
Or run the JAR file generated in the target directory:

bash
Copy code
java -jar target/sellit-0.0.1-SNAPSHOT.jar
Access the Application

Open your web browser and navigate to:

chrome browser
Copy code
http://localhost:8282
Replace 8282 with the port specified in your application.properties if different.


Contact
For any questions or issues, please reach out to aadarshdontul03@gmail.com.

