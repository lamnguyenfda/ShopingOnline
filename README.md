 * Name Project : Website shopping online BIS STORE
 * How to install :
  -  Prerequisites:
      +  Java JDK (recommended version 11 or above)
      +  Maven (for managing dependencies)
      + MySQL Server (recommended version 5.7 or above)
- Step 1: Clone the Project from GitHub
      + Open Terminal or Command Prompt.
      +  Run the following command to clone the project from GitHub:
  
  ======================================================================================== 
git clone https://github.com/your-username/your-fashion-ecommerce.git
  ======================================================================================== 
  
    + Navigate to the project directory:

 ======================================================================================== 
  cd your-fashion-ecommerce
 ======================================================================================== 
- Step 2: Configure the Database
   + Open SQL Server.
   + Create a new database with the name "fashion_ecommerce".
   + Update the database configuration information in the src/main/resources/application.properties file:
     
======================================================================================== 
spring.datasource.url=jdbc:mysql://localhost:3306/fashion_ecommerce
spring.datasource.username=your-mysql-username
spring.datasource.password=your-mysql-password
======================================================================================== 

Step 3: Build and Run the Application
     Open Terminal or Command Prompt in the project directory.
     Run the following command to build the application and install its dependencies:
     
  ======================================================================================== 
     mvn clean install
  ========================================================================================
  
Run the application using the command:

========================================================================================
mvn spring-boot:run
========================================================================================

The application will start running at the address http://localhost:8080/index

Step 4: Access the Application
Open a web browser and visit the address [http://localhost:8080](http://localhost:8080/index) to view your online Bis Store web application.
