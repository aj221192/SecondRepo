Project Title
	Expenses Management System
	
Getting Started
	This document will help you in running the project on your local machine. See deployment for notes on how to deploy the project on a your system.
	
Prerequisites
		•	Java 1.8 
		•	Tomcat 7
		•	Eclipse Neon is used to build this project (Other Framework can be used)
		•	MySQL 5.1.10
		•	Spring 4.1.5 RELEASE
		•	Hibernate 4.3.8 Final
		
Deployment
		1.	Add the project interview in to workspace
						Eclipse->File->Import->Maven->Existing Project->Browse for the project interview->OK
						
		2.	Update the Project by following	
						Right click on the project->Click on Maven->Update Project
						
		3.	Go to project properties by right clicking on interview project
		
		4.	Click on Java Build Path on left hand side and check for java system library, if it is below 1.7 remove and add new library with 					java version 1.7 (1.8 preferable)
		
		5.	Click on Java compiler on left hand menu and set it to 1.8
		
		6.	Click on Project Facets and change Java version matching with the compiler
		
		7.	Open mysql (phpmyadmin)  create a new database with name surya_test and add the given database(surya_test) which is provided in 					the same folder
				Note: No password given for mysql
				
		8.	Configure the Tomcat sever to 7 and run the project on server

