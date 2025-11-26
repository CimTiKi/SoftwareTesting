# QA Case Studies & Test Artifacts

## Introduction
This repository contains QA artifacts produced from multiple **case studies performed on practicesoftwaretesting.com**.  
All test design techniques applied here are learned and practiced from professional software testing courses and training programs.

The goal is to **strengthen test coverage, validate system quality, document bugs, and report findings** using a mix of manual and automation testing techniques.

## Scope of Study & Applied Techniques
Throughout the case studies, the following testing approaches and techniques were applied:

- **Test design**: Equivalence Partitioning, Boundary Value Analysis,Scenario Testing, Decision Table, Domain Testing
- **Automation testing**: API/UI test execution via Katalon Studio and data-driven test scripting
- **Performance testing**: Load, stress & spike scenarios created and executed in Apache JMeter
- **Cross-platform testing**: Web validation across multiple browsers and operating systems
- **UI/UX quality checks**: GUI checklist, usability testing, and user-experience validation
- **Bug tracking & reporting**: Detailed bug reports and test summaries including structured CSV reports for defect evidence

## Repository Contents
The QA package includes:

- **Test Cases** (manual and automated)
- **Bug Reports**
- **Test Automation Scripts** (Katalon Studio, JMeter)
- **Test Data Sets** for Data-Driven Testing
- **API Test Execution Reports**
- **Performance/Scenario Reports**
- **Summary Reports & CSV Test Results**

## How to Use
1. Navigate to the folder matching the type of testing you want to review or execute.
2. For automation scripts:
   - **Katalon**: Import the project or test suite into Katalon Studio and run the tests directly.
   - **JMeter**: Open the `.jmx` file in JMeter, load test data if provided, and execute the performance scenario.
3. For manual testing: Follow the test case steps and expected results, then compare outcomes with stored bug reports or summary evidence.
4. After execution, review:
   - Bug findings in `Bug_Reports/`
   - Test results and analysis in `Scenario_Reports/`, `Usability_Reports/`, or CSV summary files.

## Mission & Future Improvements
- Expand test coverage to include more edge cases, negative tests, and platform combinations.
- Add CI/CD pipeline to automatically trigger regression and performance tests on every new commit.
- Improve automation with advanced data-driven scenarios for reliability at scale.
- Maintain artifacts to help onboard new QA members and support ongoing quality reviews.


