# RedBus-Automation-Project

This project demonstrates a simple automation script for navigating the RedBus website using Python and Selenium. The script performs the following actions:

Opens the RedBus website.
Navigates to the APSRTC Buses section.
Clicks on the Hyderabad to Vijayawada route link.
Waits for elements to load dynamically on the page.
Features
Automates navigation on the RedBus website.
Demonstrates the use of Selenium for web automation.
Utilizes explicit waits to ensure smooth interaction with dynamic web elements.
Libraries Used
The script is written in Python and makes use of the following libraries:

Selenium:
webdriver: To control the browser.
By: To locate elements by their attributes.
WebDriverWait and expected_conditions: To handle dynamic web elements and explicit waits.
time: For adding delays to allow pages to load.
Prerequisites
Python 3.x installed.

Chrome browser installed.

ChromeDriver compatible with the installed Chrome version.

Required Python libraries installed. Use the following command to install them:

bash
Copy code
pip install selenium
How to Run
Clone this repository:

bash
Copy code
git clone <repository_link>
Navigate to the project folder:

bash
Copy code
cd redbus-automation
Run the Python script:

bash
Copy code
python redbus_automation.py
The script will open a Chrome browser window, navigate to the RedBus website, and perform the defined actions.

Demo
Below is a preview of the automation in action:

