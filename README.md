<img src="https://user-images.githubusercontent.com/115244741/230967229-49254e3f-b3f2-4418-9800-c96f2ce5579f.png" width="300" height="300">

# 🤨 Why taxi-service?

Taxi service is a fairly common practice in our lives, everyone has used it at least once, but few people have thought about how it works, especially from the driver's side and business logic, which is why it was interesting to understand how it works under the hood.

# 🚕 What is taxi-service?

Taxi service is a small demo application where you can register and execute the logic of managing drivers and cars. The idea of the project is to show the ability to use java servlets and sql database.

# 💡 Features
- Authentication <br />
- Add and delete drivers <br />
- Add and delete car models <br />
- Add and delete cars <br />
- Add drivers to specific cars <br />
- View all drivers <br />
- View all cars <br />
- View all cars belonging to the current driver <br />

# 💾 Getting Started
- Clone this repository <br />
- Run the SQL script located in src/main/resources/init_db.sql to initialize the database <br />
- Build the project using Maven: mvn clean install <br />
- Deploy the WAR file to a servlet container such as Tomcat or Jetty <br />

# 📜 Structure
<pre>
├───java 
│   └───taxi 
│       ├───controller                   - Controllers in which user requests are processed 
│       │   ├───car 
│       │   ├───driver 
│       │   └───manufacturer 
│       ├───exception                    - Custom exceptions 
│       ├───lib                          - Annotations and an injector that initialises our fields 
│       ├───model                        - Project models 
│       ├───service                      - The service level is intended for the operation of business logic 
│       ├───util                         - Connection to the database 
│       └───web                          - Filter for authorisation 
│           └───filter 
├───resources                            - SQL script for creating schema 
└───webapp                               - UI part of project
    └───WEB-INF
        └───views                        - All page preferences
            ├───cars
            │   └───drivers
            ├───css
            ├───drivers
            └───manufacturers 
</pre>

# 🚀 Used technologies
- Java 11 <br />
- MAVEN 4.0.0 <br />
- MYSQL 8.0.22 <br />
- JDBC <br />
- SERVLET 4.0.1 <br />
- JSP <br />
- JSTL 1.2 <br />
- CSS <br />
- TOMCAT 9.0.73 <br />
