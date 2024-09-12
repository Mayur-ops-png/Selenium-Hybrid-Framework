# Selenium Hybrid Framework

This repository contains a **Selenium Hybrid Framework** designed for automating the testing of web applications. The framework integrates multiple testing techniques, including data-driven, keyword-driven, and modular-driven approaches, making it highly versatile and scalable.

## Features

- **Modular Test Design**: Each test case is broken down into independent modules to improve reusability and maintainability.
- **Data-Driven Testing**: Tests can be executed with multiple sets of data using external data sources like Excel or CSV.
- **Keyword-Driven Testing**: Supports keyword-driven actions allowing non-technical users to contribute to test case creation.
- **Cross-Browser Compatibility**: The framework supports automation across multiple browsers like Chrome, Firefox, and Edge.
- **Test Reporting**: Generates detailed reports for test execution results using frameworks like TestNG or Extent Reports.

## Project Structure

- **src/main/java**: Contains the Java code for the framework, including utility classes, page objects, and test cases.
- **testdata**: Folder containing external test data files (Excel, CSV) used for data-driven testing.
- **drivers**: Includes WebDriver executables for different browsers.
- **testreports**: Directory where test execution reports are stored.

## Prerequisites

- **Java 8 or higher**
- **Selenium WebDriver**
- **TestNG**
- **Apache POI** (for handling Excel data)
- **Maven** (to manage dependencies and run the tests)

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Mayur-ops-png/Selenium-Hybrid-Framework.git
