# TestAutomationFrameworkApachePOI-

## Overview

TestAutomationFramework2.0 is a Java-based framework for automating web applications using Selenium WebDriver. It incorporates TestNG for executing tests, Apache POI for handling Excel files (supporting data-driven testing), and WebDriverManager for automatic management of browser drivers.

Note: The integrations for ReportNG (for advanced reporting) and Log4j (for comprehensive logging) are still in development.


## Features

- **Selenium WebDriver**: Automates browser interactions for UI testing.
- **TestNG**: Manages test execution and reporting.
- **Apache POI**: Supports data-driven testing with Excel file reading and writing.
- **WebDriverManager**: Automatically manages browser drivers.
- **ReportNG** *(In Development)*: Generates HTML-based test reports.
- **Log4j** *(In Development)*: Provides detailed logs for test execution.

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/TestAutomationFramework2.0.git
   ```

2. **Install project dependencies:**
   ```bash
   mvn clean install
   ```

3. **Run the tests:**
   ```bash
   mvn test
