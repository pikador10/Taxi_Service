# TAXI SERVICE 
***
***
This is simple Web application supports authentication, registration, other CRUD operations and simulates a work of simple taxi service.
Program has next functions:
- display all Drivers
- display all Cars
- display all Manufacturers
- create new Driver
- create new Car
- create new Manufacturer
- add driver to car
- all cars by driver
---
## 3-layer architecture
1. DAO - Data access layer
2. Service - Application layer
3. Controllers - Presentation layer
---
## Technologies
- Java 11
- Tomcat - version 9.0.50
- MySQL
- JDBC
- Servlet
- JSTL
- JSP
- HTML, CSS
---
## How to start the program
To correctly use this service you have to install MySQL and Apache Tomcat version 9.
1. Configure Apache Tomcat for your IDE.
2. Use ```/resources/init_db.sql``` for creating a Schema and tables.
3. Configure ```/util/ConnectionUtil.java``` with your URL, USERNAME, PASSWORD, JDBC_DRIVER.
4. In the ```src/main/resources/log4j2.xml``` at line ```File name = "File" fileName = "logs\app.log"``` you need to change ```logs\app.log``` with absolute path to ```.log``` file
5. Configure the tomcat library path in the startup settings.
---
## Author
```
It would be greate to hear your feedback=)
```
-    You can find me here  [Telegram](https://t.me/andrii_polikov), [LinkedIn](https://www.linkedin.com/in/andrii-poliukhovych-77b90a235/)


