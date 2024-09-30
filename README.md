# playwright-poc

## **Overview:**

This is a sample Automation project using Playwright and Typescript and uses playwright-testrunner to execute test cases. This is a Data Driven framework focused on separating the test scripts logic and the test data from each other. This allows us to create test automation scripts by passing different sets of test data. The test data set is kept in an external Excel Sheet. The test scripts connect to the external Excel sheet to get the test data. This framework significantly reduces the number of test scripts compared to a modular based framework when we need to test for multiple sets of data for same functionality.

For Demo purpose UI test cases are created on [advantageonlineshopping.com](http://advantageonlineshopping.com/) site and API test cases are created on these [SOAP API](https://www.advantageonlineshopping.com/accountservice/ws/accountservice.wsdl) & [REST API](https://fakestoreapi.com) endpoints.

## Features

- This framework has built in library to operate on UI, API (both SOAP & REST API) and DB (MSSQL, DB2 & Oracle).
- Supports execution of tests in different browsers.
- Test data is stored in an Excel sheet and from this Excel sheet user can control the test cases that needs to be run.
- User also has full control to run test in different modes from the Excel sheet.
- Allows transfer of data between test cases.
- Has utility built in for file download, Read PDF files etc.
- Generates Playwright's HTML Report, Allure Report & JUnit Report in HTML format for each exaction. 
- Allure & Playwright report including snapshots and video in case of test failure.
- Test execution logs are captured in the log file.
- You Can execute local tests in Playwright's UI Mode, that comes with a built-in watch mode. Which helps in running and debuging of tests.
- All the playwright related config is controlled by playwright config file.
- Environment variables can be modified at runtime and its controlled by .env file.
- Easy and simple integration to CI/CD tools like Jenkins.

#### Supported Browsers
1. Chrome - default browser
2. Firefox
3. MS Edge
4. WebKit - web browser engine used by Safari

