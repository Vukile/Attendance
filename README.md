# Attendance

Api
•	Api - The .Net Core 3.1 Web Api with swagger UI and Authorization
•	Common - A class library that contain common methods and custom LINQ methods that are used other projects.
•	Core - The class library where business rules are defines with use cases.
•	Infrastructure - The data layer class library where we define database for our application. In this application we SQL Server as database.

Database – 
•	The SQL Database script is under the library called Infrastructure Data>DbFile> Attend.sql
•	Execute the script on your sql server management studio in order to create the whole database. I use a local server and windows authentication.
•	The file that sets the connection is under Infrastructure > appsettings.json

Client –
The client is built on angular 11 and has its own project:  Client.
Run the Api project first.


How to run?
After cloning the Api into visual studio, switch the main attendance folder to be viewed as a solution
•	Make the Api project your startup project.
•	Make the Api your start-up project.
•	Run the project /F5.
•	You should see your default browser with the following Url: 
http://localhost:[port]/WeatherForecast
Change the link to :
http://localhost:[port]/swagger/index.html in order to test the Api.

 Generate token by registering your new user under  account register panel, login with the credentials to generate a token
•	That will give you guest rights which do not have access to most functions.

•	Once the Api is running, you can then access the client. 
•	Open command prompt, and direct to the source folder containing the client:
•	Pre-requisites: Install nodejs and angular 11 
•	>> ng serve to compile and run the interface
•	>> follow the instructions on the console in case of errors, you might have to update some modules

•	To login on the UI, use the following admin credentials :  "email": "Vntombela@yahoo.com",
  "password": "Pa$$word"
•	Navigate to the following .gif image to see how the interface runs:

 Attendance\AttendanceRegister\Common\Images



