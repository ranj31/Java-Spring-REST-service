This is Java Spring based REST service implementation.
This is maven project.

Steps tro Run the project.

1.Download the project.
2.Extract or unzipp the project.
3.Import the project in eclipse.(Maven project)
4.Add tomcat 7 server in eclipse.
5.Right click on project and choose run/debug on server.
6.server is startrd on 8080 port.

After succesfull running the server.
1.open chrome

Check the endpoints

List all employee record.
GET : http://localhost:8080/employee-management-system/employees

List only employee record from database.
GET : http://localhost:8080/employee-management-system/employees/valid employe id


Create new employee in database.

POST : http://localhost:8080/employee-management-system/employees

JSON example 
{"name": "Deepak", "designation" : "SE", "salary": "15000.00" }


Update existing employee in database.

PUT : http://localhost:8080/employee-management-system/employees

JSON example 
{"empId": 1586172498285,"name": "Deepak", "designation" : "SE", "salary": "15000.00" }

Delete existing employee from database

Delete: http://localhost:8080/employee-management-system/employees/valid employee id

 				

Technology used in this project.
1.Java 7
2.Spring Core
3.Spring REST

Endpoint testing tool : POSTMAN

Required Software and Tool to run this application. 
1.Eclipse Oxygen
2.Tomcat 7.
3.Java 7
4.POSTMAN

