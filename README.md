# Performance Test of Benefits Dashboard API

## Project Overview
This project contains a simple performance test created using Apache JMeter for the Benefits Dashboard API. The test is designed to be gentle and is intended to demonstrate basic performance testing practices rather than stress testing the application.

## Test Details
- **Tool Used**: Apache JMeter
- **Number of Threads (Users)**: 10
- **Ramp-Up Period**: 1 second
- **Thread Lifetime**: 60 seconds
- **Constant Timer**: 1000 milliseconds (1 second)
- **Test Duration**: 60 seconds

### API Endpoints Tested
1. **GetEmployees**: Retrieves a list of employees.
2. **AddEmployee**: Adds a new employee.
3. **EditEmployee**: Edits an existing employee's details.
4. **DeleteEmployee**: Deletes an employee.

## Files Included
- `PerformanceTest.jmx`: The JMeter test plan used for the performance test.
- `results_screenshot.png`: A screenshot of the test results.
- `summary.csv`: The summary of test results generated by JMeter.

## How to Run the Test
1. **Open JMeter**: Launch JMeter and load the `PerformanceTest.jmx` file.
2. **Run the Test**: Click the start button to run the test.
3. **View Results**: Use the provided listeners in the JMX file to view and analyze the results.

## Submission
Please find the test plan and test results [View the Report](https://github.com/sherkepriya89/BenefitsDashboardPerformanceTest/blob/main/index.html)
---
