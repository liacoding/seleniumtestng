<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

This project serves as a comprehensive testing framework that leverages Cucumber BDD, TestNG, and Selenium for robust UI testing. It is designed to provide an efficient and scalable solution for automated testing with a focus on maintainability and ease of use.

Key Features
- Cucumber BDD: Facilitates behavior-driven development by defining test scenarios in natural language, which helps in bridging the gap between technical and non-technical stakeholders.
- TestNG: A powerful testing framework that provides advanced functionalities like test configuration, parallel execution, and detailed reporting.
- Selenium WebDriver: Enables browser automation for end-to-end testing of web applications, ensuring comprehensive test coverage across various browsers and platforms.
  
Core Components
- Cucumber Features and Step Definitions:
  The framework includes a set of Cucumber feature files that outline test scenarios in Gherkin language. Each scenario is linked to corresponding step definitions that implement the test logic.
  
- Driver Utility with Singleton Design Pattern:
  Implements a singleton design pattern to manage the Selenium WebDriver instance, ensuring that only one instance of the driver is created and reused throughout the test suite.
  
- Configuration Properties with Configuration Reader:
  Configuration properties are centrally managed, and a configuration reader is provided to access these properties. This approach allows for easy modification and management of configuration settings without altering the codebase.
  
- Utility Methods with Selenium WebDriver:
  The framework includes a set of utility methods for common Selenium WebDriver operations, such as element interaction and browser navigation, to streamline test development and reduce code duplication.
  
- Page Object Model (POM) Concepts:
  Adopts the Page Object Model pattern, which encapsulates page elements and actions within page classes. This approach promotes a more centralized and maintainable structure, facilitating easier updates and enhancements to the test scripts.




### Built With
- <img src="https://img.shields.io/badge/Cucumber-43B02A?style=for-the-badge&logo=cucumber&logoColor=white" />
- <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=Selenium&logoColor=white" />
- <img src="https://img.shields.io/badge/Java-f89820?style=for-the-badge&logo=java&logoColor=white" alt="Java Badge" />
- <img src="https://img.shields.io/badge/TestNG-8A2BE2?style=for-the-badge&logo=testng&logoColor=white" alt="TestNG Badge" />



<!-- GETTING STARTED -->
## Getting Started

- Ensure you have the following installed on your machine: JDK, Maven, Git
- Clone the repository
- Install the dependencies with 'mvn clean install' command
- Update your configuration files in configuration.properties

<!-- USAGE EXAMPLES -->
## Usage

This testing framework provides a solid foundation for automating UI tests with Cucumber BDD, TestNG, and Selenium. Its structured approach and reusable components ensure that you can easily scale and maintain your automated tests as your application grows.
