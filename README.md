# PlexusAssignment

# Description: This is the foundation for testing the function of cypress.io
The feature file only specifies the function "type" inorder to stick to the requirements of the assignment
The glue code implements more functions like type, submit, clear, select, click and check.
These can be specified in the featureFile in the datatable format

The test is implemented for Windows-Chrome. ChromeDriver executable is part of the repo.

To run from commandline
-------------------------
Checkout the project

From the root dir, run the command : mvn compile test

To run from IDE
-----------------
Download the repo.

Import the project as Maven-> Existing Project.

Right click on the project -> Maven clean -> Maven Compile.

Right click on the project -> Run as -> JUnit test  or Right Click on the featureFile-> Run as Cucumber feature

