
# This is test automation task for Geocoding API

Used tool is SoapUI.


Steps to execute the tests:

1. Download SoapUI tool, version 5.3.0 (Link for download:https://www.soapui.org/downloads/soapui.html)
2. Download or clone the repo with code
3. Import downloaded project into SoapUI
4. Run the Geocoding API Test Suites

To execute tests from command line:

1.Setup soapUI bin folder into your system variable path
2.Open command prompt and go to destination of soapUI project
3. Run command >testrunner {SoapProjectName}.xml
4.After running test you should see some text file is generated in root
5.  We can run test suite or test case using testrunner command. as below:

testrunner –c "Geocoding Test Cases" -r abhTask.xml

Where “Geocoding Test Cases is test name and “abhTask.xml” is soapui project. 

Launching the Test Runner from within SoapUI

1. Project is downloaded and imported into SoapUI 
2. Right-click on it and click on Launch Test Runner
3.Launch Test Runner is opened where it posible to choose which Test Suite, Test Case to run
4. In the Launch Test Runner inside tab Reports we can specify type of report for results of executed Test case
5.When executing is finshed inside in opened window we could see actual command issued at the command-line.
6.Copy and paste this into automation tool for rerun these tests as configured.





