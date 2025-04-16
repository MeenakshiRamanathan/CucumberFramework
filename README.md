**SKILLS GAINED:**  

Test Automation Framework Design  
Behavior-Driven Development (BDD)  
TestNG Configuration and Execution  
Advanced Reporting with ExtentReports  
Selenium WebDriver Automation  
Maven Build and Dependency Management  
Agile Testing Skills  
Modularization and Code Reusability  
API Testing and Configuration  
Debugging and Issue Resolution  

**Top-Level Directories**

**testng.xml:** TestNG configuration file that specifies which test classes or groups to run, along with configurations like listeners or parallel execution.  

**pom.xml**: Maven's Project Object Model file that manages project dependencies, build plugins, and project information.  

**Source Code Structure**  

**src/main/java**  
 **_meenakshi_Automation_**  
  Contains the following POM Pages  
    GmailLandingPage  
    NaukriLandingPage  
    NaukriOTP  

**_utils_**  
   Utility  
   Contains reusable functionalities  

**src/test/java**  
**_meenakshi1_Automation_**  
  base/  
  Handles WebDriver setup and teardown  
  
**_resources_**  
config.properties/  
Login_stepDefinition.feature/  
Cucumber feature file describing Dashboard page scenarios in Gherkin syntax.  

**_stepDefinition_**  
   **Login_stepDefinition.java/**   
   Step definition file containing Cucumber steps for Dashboard-related features.  
   **runner.java/**   
   Entry point for executing Cucumber tests using the Cucumber TestNG runner.  

**Key Points of This Structure**  
**Maintainability:**    
Clear segregation of page objects, utilities, step definitions, and feature files.  

**Reusability:**    
Centralized utilities (e.g., DriverManager) and separate page classes ensure reusable components.  

**BDD Best Practices:**  
Using Gherkin for feature files and keeping step definitions tied to logical feature areas.  

**Reporting:**  
Integration of ExtentReports/SparkReport for comprehensive and visually appealing test reporting.  

**Modularity:**  
Adding new features or pages is simple due to this structured approach.  
