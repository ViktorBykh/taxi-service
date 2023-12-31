#  <h1 align="center"> <img src="https://em-content.zobj.net/thumbs/120/apple/354/oncoming-taxi_1f696.png" width="35"/> Taxi-Service  <img src="https://em-content.zobj.net/thumbs/120/apple/354/oncoming-taxi_1f696.png" width="35"/> </h1>

## <img src="https://em-content.zobj.net/thumbs/120/apple/354/light-bulb_1f4a1.png" width="30"/> **Project description:**
`A simple web-application that supports authentication, registration and basic CRUD operations.` 

### <img src="https://em-content.zobj.net/thumbs/120/apple/354/direct-hit_1f3af.png" width="20"/> Features:
* registration like a driver;
* authentication like a driver;
* create/update/remove a car;
* create/update/remove a driver;
* create/update/remove a manufacturer;
* display list of all cars;
* display list of all drivers;
* display list of all manufacturers;
* display the car of the current driver;


### <img src="https://em-content.zobj.net/thumbs/120/apple/354/gear_2699-fe0f.png" width="20"/> Project Structure
The project follows a standard structure to organize the code and resources:
* `controller`: Contains servlets that handle HTTP requests and responses;
* `dao`: Contains data access objects for database operations;
* `exception`: Contains custom exception classes;
* `lib`: Contains dependency injectors;
* `model`: Contains domain models (entities);
* `service`: Contains business logic and services;
* `util`: Contains utility class used for managing database connections;
* `webfilter`: Contains the class used to authenticate user requests.
* `resources`: Contains the script used to initialize the database schema
* `webapp`: JSP files, CSS files, and the web.xml deployment descriptor;


### <img src="https://em-content.zobj.net/thumbs/120/apple/354/clamp_1f5dc-fe0f.png" width="20"/> Technologies used:
* <img src="https://image.emojipng.com/677/13219677.jpg" width="30"/> Java 11

* <img src="https://storage.googleapis.com/zenn-user-upload/bcc525adcbd9-20220606.jpg" width="30"/> JSTL 1.2
* <img src="https://www.unicodesystems.us/img/core-img/jdbc1.jpg" width="30"/> JDBC API 8.0.28
* <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTXOiLvoU4lULzGb-hekaL8txhP1r-_W78DCrOQfz_9nO-InKmJuoQu8EKIq1Q0NwoMDdw&usqp=CAU" width="30"/> Servlet API 4.0.1
* <img src="https://logowik.com/content/uploads/images/t_css3-html51661.jpg" width="30"/> HTML/CSS
* <img src="https://cdn.fs.teachablecdn.com/L2rtxPaRxa4am1VtNegghttps://cdn.fs.teachablecdn.com/L2rtxPaRxa4am1VtNegg" width="23"/> Maven 3.1.1
* <img src="https://logowik.com/content/uploads/images/mysql8604.logowik.com.webp" width="23"/> MySQL 8.0.22
* <img src="https://img.icons8.com/color/100000/000000/tomcat.png" width="23"/> Tomcat 9.0.50

### <img src="https://em-content.zobj.net/thumbs/120/apple/354/nut-and-bolt_1f529.png" width="20"/> Instructions for launching the project
To run the Taxi-Service project, please follow these steps:
* Make sure you have Java 11, Maven 3.1.1, MySQL 8.0.22 installed on your system
* Fork the project from the [repository](https://github.com/ViktorBykh/taxi-service)
* To clone the project, click on the "Code" button and select either the HTTPS or SSH URL
* Configure [Apache Tomcat](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/) version: 9.0.50
* Create a MySQL database by executing the SQL script located in the resources - [init_db.sql](src/main/resources/init_db.sql)
* To set the necessary parameters, edit the [ConnectionUtil.java](src/main/java/taxi/util/ConnectionUtil.java) file:
  * [x] private static final String URL = "URL";
  * [x] private static final String USERNAME = "USER NAME"; 
  * [x] private static final String PASSWORD = "PASSWORD"; 
  * [x] private static final String JDBC_DRIVER = "JDBC DRIVER";
* Run the project

### Try the working version:
[Taxi-service](http://taxi-service.eu-west-2.elasticbeanstalk.com)
