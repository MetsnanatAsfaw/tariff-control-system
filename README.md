# Tariff-Web

#Introduction

Problem of transportation is common in our country . We dare to say we all face this in our daily life activities especially those related to tariff . In one way or another we see when people ruggedly speak about tariff increasing every day . This problem is not a problem of government rather it is the problem with the driver especially when the passenger on board is strange. As a group we think and come with the solution, a software that controls this problem.

#Business feature
This software system is a web application which-
-	will enable a passenger to check the tariff. 
-	allow registered users to report when they face illegal tax raise. 
-	allow authorized person to check number of records.

The system contains a database which provides 
-	List of station with their tariff
-	List of cities in Ethiopia with their tariff from addis ababa.
-	List of traffic’s name and ID

we have two interface one for the user to login and other for traffic to login so we need both authentication and authorization:

authentication
- identity of the user has to be verified using password and email.
- identity of authorized user for example tiraffic is checked using identity number(ID) in addition to password and email.
              
authorization
- all users of the system have privilege to check tariff. In addition registered user have privilege to report illegal tariff raise scenario.
- the system give permission to authorized user to check drivers record.
- the system grant permission to authorized user to create,read,update and delete database.

