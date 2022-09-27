# Code-Louisville-Quality-Project-Teresa-Hawkins

 QA Testing Project Instructions:

To run the project do the following: Clone github.com/deartc/Quality-Project-Teresa-Hawkins. (Any other instructions I need to include goes here).  The extensions used were C# and Net.  The NuGets used were xunit and others.  


 
                                           ASSIGNMENT # 1/#2  -  VERIZON TEST PLAN/PRESENTATION/BUG REPORT 
  
 


#1: Test Plan

Introduction


Verizon is an Internet, phone, and TV provider that has one of the best retention rates of customers (churn) in the world. One of the main reasons is the website tries to engage customers. For this project, I have analyzed the  hypthetical updated feature in the Verizon checkout.   I have completed the following: A: a test presentation on the Verizon site. I have attached the test plan detailing steps I took. B: Manual Test Execution I am presenting the results of my manual test execution. C. I am also attaching a bug report.  I did a Microsoft Sway as well as a plain text portion.
 


Scope 
 
Inclusions  The testing primarily dealt with the checkout process   I identified ten tests I peformed on the websites which falls into one of these major categories: critical path, regression, non-functional.   l  included all of the necessary components of each test case (preconditions, steps,  and expected resuls.
 
Exclusions   The testing was restricted  to this major feature and I did not include more that ten tests, although other tests could have been performed. 


1.	HTML/CSS Validation 
Verizon was validated by entering its URL and checked by the HTML Validator extension for Chrome. 
 preconditions- The precondition for HTML/CSS Validation  is that I used the URL listed as the official Verizon HTML
  steps-The steps for HTML/CSS Validation was checked by the HTML Validator extension for Chrome
  expected results-The expected results for HTML/CSS Validation is that it passed. 
  
  2. Black Box Testing - Form Input and Validation 
  Verizon site  was checked for data input validity and what happens when there are invalid inputs 
  preconditions- The email must be valid form.  The password must fit the criteria (upper case,lower case, number, special character, and minimum charcters.   
  steps, I inputted several emails.  Two valid and two invalid.    I inputted several passwords. Two valid and two invalid 
  expected results-  The valid email and passwords passed.   The invalid email and passwords failed.

	

3. Cookie Testing   Cookies was tested with cookies disabled and cookies enabled.   Geekflare was used for cookies’  security issues
 preconditions- Geekflare was used for cookies’  security issues
  steps- Cookies was tested with cookies disabled and cookies enabled. 
  expected results- Cookies was tested with cookies disabled and cookies enabled and they passed. 

 4.  Link Testing- To test for Verizon broken links, Broken Link Checker was used to see if there were broken links. Key linages were also tested for proper page. 
  preconditions- Broken Link Checker was used to see if there were broken links 
  steps-  Several key links were also tested to ensure goes to the proper page and if there were broken links.
  expected results- Verizon key links  go to the proper page and  there were no  broken links.
  
  5. Website Security- Verizon’s SSL/HTTPS connection was tested to make sure it's working properly.  
 preconditions- Verizon’s SSL/HTTPS connection was checked ensuring that the HTTPS connection was present. The  password should be in encrypted format
  steps- Verizon’s SSL/HTTPS connection was checked by looking at CAPTCHA and typing in the correct answer 
  expected results-The CAPTCHA was checked  for proper functioning and it worked. The  password was in encrypted format   
  
  6. Mobile Responsiveness Verizon site was tested using Google's Mobile-Friendly Test. 
 preconditions-  Mobile Responsiveness Verizon site was tested using Google's Mobile-Friendly Test on a Android phone
  steps-  Google's Mobile-Friendly Test was used on a Android phone.  Mobile Responsiveness  on the Verizon site was tested to see if the layout was presentable  
  expected results- Mobile Responsiveness testing  on the  Verizon site indicated the layout was up to standards and  the links worked.
  
  7. Accessibility on the  Verizon  site was tested against the Web Content Accessibility Guidelines (WCAG).   W3C maintains a list of web accessibility evaluation tools that you can use to help you test your site.
   preconditions- W3C  list of web accessibility evaluation tools were used to  test Verizon site.
  steps-  Accessibility on the  Verizon  site was tested against the Web Content Accessibility Guidelines (WCAG).
  expected results- Accessibility testing on the  Verizon  site against the Web Content Accessibility Guidelines (WCAG) passed.
  
  8.  Functionality Testing.  Verizon functionality testing was performed The following were tested : drop-downs, buttons  and process flow .
 preconditions-  The preconditions for the Verizon functionality testing was to identifiy the  drop-downs, buttons  and process flow 
  steps- Verizon functionality testing was performed The following were tested : drop-downs, buttons  and process flow. 
  expected results- Verizon functionality passed the following tests : drop-downs, buttons  and process flow. 

9.  Payment Gateways    Payment gateways on Verizon were tested. to make sure they're working.
preconditions- The preconditions of the payment gateways testing
  steps- The steps of the payment gateways testing
  expected results- The expected results of the payment gateways testing is that it passed

10. UI Testing. UI testing on the Verizon site included checking  design consistency, screen resolutions and browsers
 preconditions- The preconditions of UI testing on the Verizon site  is setting a minimum standard for design consistency, screen resolutions and browsers.
  steps- UI testing on the Verizon site included checking  design consistency, screen resolutions and browsers.
  expected results-    The UI testing on the Verizon site passed in relation to   design consistency, screen resolutions and browsers.
  
  
  
  
2.   A test report and a  hypothetical  bug report  in Microsoft Sway and in  text format

Test Form   https://sway.office.com/wPGb2CIaQVvXvN66?ref=Link

BUG REPORT FORM    https://sway.office.com/iwzfKDyrqIs2oDxY?ref=Link 

BUG REPORT FORM

SUBMITTED BY	DATE
Teresa Hawkins	 9/27/22
			
FILE ATTACHMENT(S)
Hypothetical	 
			
REPRODUCIBILITY   
10 out of 10 times	

TIME OF OCCURRENCE 
9/27/2022 12:29 P:M EST
 	 	 	 
EXACT URL
www.verizon.com

BUILD VERSION
 Desktop
 	 
			
ACTION PERFORMED   
Put in valid promotion code and not accepted

ERROR MESSAGE  Promotion is not valid
 	 
EXPECTED RESULT  Promotion code accepted and discount present

ACTUAL RESULT  Promotion code not accepted and discount not present
 	 
			
FREQUENCY			
Every Time    X	    	 

Status: Supervison fixed on 9/27 at 6:15 p.m.  EST
 
 	 	 	 	 	 
 

 
 
 
 
   
   
   
   
   
   
   
   
   
   
   
   
            #3.  UNIT TEST PROJECT:
   

Requirements of classes completion: 
1. On the Vehicle class, add unit tests  and refactor where necessary.
2. On the SemiTruck class,  implement all methods and write unit tests 
3. Add 3rd class, Car, implement it, and add unit tests for it. 




Unit tests requirementss:
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


