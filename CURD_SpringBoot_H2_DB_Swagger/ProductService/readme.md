This Application is a small CURD operation using Java , Springboot, H2 Database (In-memory DB)

After start the application browse with below details.

API Document :  http://localhost:4201/swagger-ui.html


Database Details: 
DB Url: http://localhost:4201/h2-console  
JDBC URl : jdbc:h2:mem:emp_db 
UserName:sa
password :  


By default the port is 4201, But you can change the port inside application.properties file 
ex: server.port=8085


Note: I have written code to open in default browser, if page is blank just refresh after 10-15 second



If you want to import this project
In eclipse import as a existing maven project and do below steps in eclipse/command line

mvn update
mvn clean install
mvn spring-boot:run
