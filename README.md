# Subscription-Jawwy-TV
Automation script test subscription package - type , price, currency
This Java-based automation script uses Selenium and TestNG to test subscription package types, prices, and currencies on a website.

Installation
To run this script, you will need to have Java, Selenium, and TestNG installed on your machine. You can download Java from the official website, and Selenium and TestNG can be installed using Maven or Gradle.

Usage
To use this script, first clone the repository to your local machine:

git clone https://github.com/yourusername/Subscription-Jawwy-TV.git
Then, navigate to the project directory and run the following command to execute the test:

mvn clean test
This will run the test, and the results will be displayed in the console.

Test Cases
This automation script tests the following scenarios:

Verify that the correct subscription package type is displayed on the page.
Verify that the correct price is displayed for the selected subscription package type.
Verify that the correct currency symbol is displayed for the selected subscription package type.
Test Data
 This file contains the following information for each subscription package type:

Package type name
Package price
Currency symbol
Test Steps
The script follows these steps to test the subscription package type, price, and currency:

Launch the website.
Navigate to the subscription page.
Read the subscription package type, price, and currency symbol from the JSON file.
Select the subscription package type on the page.
Verify that the correct subscription package type is displayed on the page.
Verify that the correct price is displayed for the selected subscription package type.
Verify that the correct currency symbol is displayed for the selected subscription package type.
Close the browser.
Conclusion
This automation script provides a reliable and efficient way to test subscription package types, prices, and currencies on a website. By using Java, Selenium, and TestNG, we can ensure that our tests are accurate and repeatable, providing confidence that the website is functioning as expected.
