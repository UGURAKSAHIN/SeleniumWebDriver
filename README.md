# Automated Login Testing with Selenium & TestNG

# Project Overview

This project automates the process of logging into a web application using Selenium WebDriver and TestNG. The script performs login tests using multiple usernames and passwords and verifies the authentication results. It also checks for invalid login attempts and ensures error messages are correctly displayed.

# Features & Functionality

- Navigates to a specified URL using Selenium WebDriver
- Tests multiple username-password combinations
- Validates successful login attempts
- Detects and verifies error messages for invalid logins
- Uses TestNG for structured test execution and reporting

# Tech Stack & Tools Used
- Programming Language: Java
- Testing Framework: TestNG
- Automation Tool: Selenium WebDriver
- Dependency Management: Maven
- Browser: Chrome (via ChromeDriver)

# Installation & Setup

1. Prerequisites

-Java JDK (11 or later)

-Maven

-Chrome Browser

-ChromeDriver (compatible with your browser version)

2. Clone the Repository
   
git clone https://github.com/your-repo/selenium-login-test.git
cd selenium-login-test

3. Install Dependencies

mvn clean install

4. Configure WebDriver

System.setProperty("webdriver.chrome.driver", "path/to/chromedriver");

# Running the Tests

mvn test

# Run Specific Test Class

mvn test -Dtest=LoginTest

# Run Using testng.xml

mvn test -DsuiteXmlFile=testng.xml
