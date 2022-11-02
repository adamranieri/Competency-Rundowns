# Test Automation
By Adam Ranieri

### Definition
Test Automation is the ability to write programmatic tests. Often, test automation refers to the ability to write automated tests for testing Web App UIs. These tests run independently of any framework used to create the front end. These automated tests could be written in any language. Automated tests are usually coded with Selenium. Selenium libraries are available in a variety of programming languages. Gherkin is used to write user stories/ test cases for most automation testing purposes.

### Abilities
-	Turn user stories and business requirements into Gherkin features
-	Create step implementations from Gherkin scenarios
-	Use selenium to implement glue code/ step implementations
-	Use selenium to navigate to web pages
-	Use selenium to interact with web pages
    -	Fill out forms/inputs
    -	Click on buttons
    -	Read web elements
    -	Use waits to interact with elements
-	Locate web elements using different selectors
-	Write dynamic Xpath for use as a selector
-	Xpath creation must be done without the aid of tools
-	Create Page Object Models to organize automation tests

### Trainer Advice
-	Selenium is a very broad and shallow subject. 
    -	Anything that could be done on a web page is possible to do with selenium. 
    - Almost anything programmable in selenium is a quick google search of being able to accomplish
-	It is very difficult to try and account for all the possible questions one could ask in an interview. 
    -	You should prioritize giving associates as much selenium practice as possible. 
    -	This will force them to use waits, and more obscure features of selenium to achieve their goals. 
-	Selenium and Gherkin are easy to conflate. Selenium is chocolate and Gherkin is peanut butter. 
    -	Separate things that pair together really well.
-	Xpath is a very popular interview question. 
    -	Being able to get Xpath from the browser console will not pass scrutiny with interviewers


## Assessment

### Green Flags
- Associate can write automation tests from Gherkin feature files with no guidance
- Associate can intelligently use google and documentation to interact with difficult web elements or perform unique actions
- Associate can write basic Xpaths without the aid of notes or google searches
- Associate creates POMs to logically organize their automation tests

### Red Flags
- Associate can only do Xpath from the console
- Associate cannot set up POMs
- Associate treats selenium and cucumber like they are the same thing

### CAPs

| Bounty | Type | Duration | CAPs |
|--------|------|----------|------|
| [BugCatcher](https://github.com/adamranieri/TestAutomation-CAPs/tree/main/Bug-Catcher)| Project | 40+ hours| 10 |
| [inFormed](https://github.com/adamranieri/TestAutomation-CAPs/blob/main/bounty-inFormed.md) | Coding Activity | 6 -8 hours | 4|
| [Actions API](https://github.com/adamranieri/TestAutomation-CAPs/blob/main/bounty-Action-API-Practice.md) | Coding Activity | 2 hours | 2 |
| [Build A Site](https://github.com/adamranieri/TestAutomation-CAPs/blob/main/bounty-Build-a-Site.md) | Coding Activty | 4 hours | 2 |
| [Xpath Hero](https://github.com/adamranieri/TestAutomation-CAPs/blob/main/bounty-Xpath-hero.md) | Coding Activity | 2 hours | 2 |
| [E2E Tests On Project](https://github.com/adamranieri/TestAutomation-CAPs/blob/main/bounty-e2e-tests-p2.md) | Project | 40+ hours | 4 |
| [Automation Exam](https://app.revature.com/admin-v2/quiz/view/6882) | Exam |1 hour | (Exam Score % * 10) - 7 |

#### Rubric
-	20+
    -	Very Solid understanding of Test Automation
    -	Should be able to work independently
    -	Completed many practical applications requiring selenium
-	14-19
    -	Solid understanding of Test Automation
    -	Completed several practical applications
    -	Should have a solid understanding of Test Automation
-	9-13
    -	Has a basic understanding of test automation
    -	Should be able to test automation on really simple web pages 
    -	Will have to google how to do most things in selenium
-	0-8
    -	Minimal understanding of Test Automation
    -	Strong associates might get the concept and do it independently
    -	Weak associates will likely be unable to do anything useful or explain anything behind rote definitions


