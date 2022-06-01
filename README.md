Cohort Code : INTQEA22QE068
Group No. : 4
Project Type :MAIN PROJECT
Project Title: WORLD CLOCK 
------------------------------------------------------------
------------------------------------------------------------

***************************  MAIN PROJECT ***********************************

Problem Statement:
                 Navigate to world clock and check functionality

Detailed Description: 

	1.Open url-> be.cognizant.com
	2.Login using cognizant credentials
	3.After opening of be.cognizant.com fetch the user details
	4.Scroll down to the bottom of the be.cognizant homepage and then check world clock details
	5.Now capture the time at present and then again capture time for 6hrs later

Technology/Automation Tools used:
1.Selenium Webdriver and it's concepts
2.TestNG Framework and it's concepts
3.Data Driven approach
4.Core Java Concepts
5.Maven/Apache POI tools
6.Extent Report/TestNG Report/Customized Report
7.Cross Browser Testing Concepts
8.Property file concepts
              

Browser Options:
	1.Chrome
	2.Firefox
	(The browser is mentioned in the testng.xml, to run the various browser make changes in value field).


Structure Details:
	1.src/main/java:
		Base Package->Browser,Reusable Methods,Screenshot,Config.properties.
	2.Pages package:
		-> WorldClock.java
	3.Utils package:
		ExtentReportManager.java
		(This package contain extent report files to create an extent report).
	4.src/test/java:
		TestSuites package-> WorldClockTC.java
		(This file contain the TestNG script to automate the code).
        5.src/test/resources:
              MS Excel file- Data.xlsx

Readme:It contains the problem statement and detailed explanation about project file.

Reports:It contains the extent report for the automated project file.

Screenshot:It contains the screenshot taken during the execution of the program.

    Team Members               Employee Id
-----------------------               ----------------- 
  Chandana Nagendran		  2152630
  Abhishek Singh			  2153080
  Lovish Seth			  2151701
  Md Rahamat Ali			  2152346
  Manaswini Reddy		  2152565
  Preethi Vardhan			  2152413
