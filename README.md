Robot_framework
The "Framework" directory contains the core components of the automation framework.

===>Resources: This directory holds the Page Objects, Variables, and Keywords.

  --->Page Objects: Contains Robot Framework test case libraries for page objects.
          login_PO.robot: Page Object library for the login page.
          registration_PO.robot: Page Object library for the registration page.
          
  --->Variables: Stores various variable files.
          common_variables.robot: Common variables used across test cases.
          login_variables.robot: Variables specific to the login functionality.
          registration_variables.robot: Variables specific to the registration functionality.
          
  --->Keywords: Stores reusable keywords.
          common_keywords.robot: Keywords that are commonly used across test cases.
          ui_keywords.robot: Keywords related to user interface interactions.
          api_keywords.robot: Keywords related to API testing.
          database_keywords.robot: Keywords related to database interactions.
   
===>TestCycles:  directory is where you organize your test cases into modules and scenarios.

  --->Module 1 folder: Contains test scenarios related to Module 1.
          login_testcase1.robot: Test case for Module 1, Test Case 1.
          reg_testcase1.robot: Test case for Module 1, Test Case 2.

  --->Module 2 folder: Contains test scenarios related to Module 2.
          login_testcase2.robot: Test case for Module 2, Test Case 1.
          reg_testcase2.robot: Test case for Module 2, Test Case 2.
