# Code-Louisville-Quality-Project-Teresa-Hawkins

 QA Testing Project Instructions:

To run the project do the following: Clone github.com/deartc/Quality-Project-Teresa-Hawkins. (Any other instructions I need to include goes here).  The extensions used were C# and Net.  The NuGets used were xunit and others.  


 
 Assignment 1  -Test Plan  For Verizon 
  
 
Test Plan
 
1	Introduction


Verizon is an Internet, phone, and TV provider that has one of the best retention rates of customers (churn) in the world. One of the main reasons is the website tries to engage customers. For this project, I have analyzed the checkout at the Verizon   I have completed the following: #1: Test Plan - I completed a test plan on the Verizon site. I have attached the test plan detailing steps I took. #2: Manual Test Execution I am presenting the results of my manual test execution. I have attached the following presentation detailing the manual test execution.
 

#1: Test Plan
I completed a test plan on the Verizon site.  I have attached the test plan detailing steps I took.

https://sway.office.com/zBIxDmNBKuwC0Xrn
	

	
I have included a bug report


https://docs.google.com/document/d/1lz6yAHhdLGvTMFdzE5x1BHlp_YM46QLf-5CqcqOLzjI/edit?usp=sharing


 Scope 
 
Inclusions  The testing primarily dealt with the checkout process   I identified ten tests I peformed on the websites which falls into one of these major categories: critical path, regression, non-functional.   l  included all of the necessary components of each test case (preconditions, steps,  and expected resuls.
 
Exclusions   The testing was restricted  to this major feature and I did not include more that ten tests, although other tests could have been performed. 

   


Functional
Non – Functional
Maintenance

Non-functional testing should increase usability, efficiency, maintainability, and portability of the product.  Non functioning 
1.	 Black Box Testing - Form Input and Validation 
  Verizon site  was checked for data input validity and what happens when there are invalid inputs 
  preconditions- 
  steps-
  expected results-

2.	HTML/CSS Validation 
Verizon was validated by entering its URL and checked by the HTML Validator extension for Chrome. 
 preconditions- 
  steps-
  expected results-

3. Cookie Testing   Verizon was tested with cookies enabled and cookies disabled to ensure functionality.   Geekflare was used for cookies’  security issues
 preconditions- 
  steps-
  expected results-

 4.  Link Testing- To test for Verizon broken links, Broken Link Checker was used to see if there were broken links. Several key links were also tested to ensure goes to the proper page 
  preconditions- 
  steps-
  expected results-

5.Website Security- Verizon’s SSL/HTTPS connection was tested to make sure it's working properly.  
 preconditions- 
  steps-
  expected results-TheCAPTCHA were checked  for proper functioning.   Invalid username or password were tested.  Sample Test scenarios to give you a glimpse of security test cases.

A password should be in encrypted format
Application or System should not allow invalid users
Check cookies and session time for application

6.Mobile Responsiveness Verizon site was tested using Google's Mobile-Friendly Test. 
 preconditions- 
  steps-
  expected results-

7.  Accessibility on the  Verizon  sitr was tested against the Web Content Accessibility Guidelines (WCAG).   W3C maintains a list of web accessibility evaluation tools that you can use to help you test your site.
   preconditions- 
  steps-
  expected results-
  
8  Functionality Testing.  Verizon functionality testing was performed The following were tested : drop-downs, buttons  and process flow .
 preconditions- 
  steps-
  expected results-

9.  Payment Gateways    Payment gateways on Verizon wwre tested. to make sure they're working.
preconditions- 
  steps-
  expected results-

10. UI Testing. UI testing on the Verizon site included checking  design consistency, screen resolutions and browsers
 preconditions- 
  steps-
  expected results-
 
   Defects Classification Mechanism
 
Type of Defects 	Functionality 	Performance 	Security 	Usability	Compatibility 
Critical	 	 	 	 	 
Major	 	 	 	 	 
Minor	 	 	 	 	 
Cosmetics	 	 	 	 	 
 


 Unit Test/Coding Requirement of Project:

  
1. On the Vehicle class, add unit tests  and refactor where necessary.
2. On the SemiTruck class, I will implement all methods and write unit tests 
3. Add 3rd class, Car, implement it, and add unit tests for it. 
This is the list of tests:
1.	parameterless constructor -object of type Vehicle, 
2.	Vehicle, -public properties to the provided values.
3.	 parameterless AddGas method fills the gas tank to 100% of its capacity
4.	 AddGas method with a parameter adds the supplied amount of gas to the gas tank.
5.	AddGas GasOverfillException – how much add and what the capacity was.
6.	 GasLevel -a  0%, 25%, 50%, 75%, and 100%..  (theory test)
7.	Drive method: without gas returns the status string “Cannot drive, out of gas.”
8.	 drive a car - flat tire returns the status string “Cannot drive due to flat tire.”.
9.	Drive the car 10 miles. GasLevel MilesRemaining mileage correct.
10.	Drive the car 100 miles. GasLevel MilesRemaining mileage correct.
11.	Out of gas. GasLevel MilesRemaining mileage correct.
12.	ChangeTireAsync will throw a NoTireToChangeException 
13.	ChangeTireAsync can successfully be used to change a flat tire
14.	 GotFlatTire method Refactor GotFlatTire can be both true and false. 
15.	 SemiTruck object which is also a Vehicle and has 18 wheels. V
16.	Cargo property -CargoItems which is empty, but not null.
17.	LoadCargo: correctly adds the passed object to the Cargo.
18.	UnloadCargo Positive Test: remove  from the Cargo and return cargo 
19.	CargoIUnloadCargo Negative Test: Verify that attempting to unload a CargoItem that does not appear in the Cargo throws a System.ArgumentException.
20.	GetCargoItemsByName Positive Test: item that exist returns all items wit exactly that name. 
21.	GetCargoItemsByName Negative Test: does not exist returns an empty list.
22.	GetCargoItemsByPartialDescription Positive Test: contain that Description.
23.	GetCargoItemsByPartialDescription Negative Test does not exist returns an empty list.
24.	GetTotalNumberOfItems: sum of all quantities of all items in the Cargo List.
25.	Car instances are also Vehicles and have 4 tires.
26.	IsValidModelForMakeAsync test: 
27.	WasModelMadeInYearAsync Negative Test: before 1995 System.ArgumentException.
28.	WasModelMadeInYearAsync Positive Tests:  Make that does not exist at all returns false
29.	Make Honda, Model Camry returns false (regardless of year).
30.	Make Subaru, Model WRX returns true for year 2020.
31.	Make Subaru, Model WRX returns false for year 2000.
32.	AddPassengers test: reduces the fuel economy of the car by .2 per passenger.
33.	RemovePassengers test:  Car with 5 passengers that gets 21 MPG.
34.	RemovePassengers  2 passengers and gets 20.6 MPG.
35.	RemovePassengers 0 passengers and gets 21 MPG
36.	RemovePassengers 0 passengers and gets 21 MPG.
37.	Methods-  vehicle
38.	 Methods- semitruck
39.	Method- car


the first steps of the code are included here: https://github.com/deartc/CarSection.git


