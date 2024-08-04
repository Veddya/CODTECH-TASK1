Name : Vedant Mahajan
Company : Codtech IT Solutions
ID :CT6WDS1482
Domain : Software Testing
Duration : 1st Aug to 15th Sep 2024
Mentor : Muzammil Ahmed

Overview of the project 
project: Perform functional testing on a web application using Selenium
WebDriver.Write test scripts to automate web application interactions. 
Use Selenium WebDriver to execute tests in different browsers.

Objective:
The objective of this project is to perform functional testing on a web application using Selenium WebDriver. 

This involves:
Setting Up Selenium: Integrate Selenium WebDriver into the testing environment.
Automating Interactions: Write test scripts to automate user interactions with the web application (e.g., form submissions, navigation).
Cross-Browser Testing: Execute tests in different browsers (e.g., Chrome, Firefox) to ensure cross-browser compatibility.
Validation: Use assertions to validate the expected outcomes of the automated interactions.

Benefits:
Automate repetitive testing tasks.
Ensure the web application functions correctly across different browsers.
Improve the efficiency of the testing process.

Test Scripts:

Setup and Teardown:
The @BeforeEach method sets up the WebDriver instance. You can switch between browsers by commenting or uncommenting the appropriate lines. Make sure to set the correct path to the WebDriver binaries.
The @AfterEach method closes the browser after each test.

Test Methods:
testSuccessfulLogin: Tests a successful login scenario by providing valid credentials and verifying the URL after the login.
testFailedLogin: Tests a failed login scenario with invalid credentials and checks for the presence of an error message.

