# Fintech App API and Functional Testing Project

## Overview
This project is a demonstration of API and functional testing skills developed as part of my application for the Software Quality Analyst (SQA) . It includes manual test cases, API testing using Postman, and a basic functional test of a mock Fintech application. The project aligns with focus on quality assurance for products spanning web and mobile platforms.

## Project Details
- **Purpose**: To showcase the ability to create test plans, execute tests, identify bugs, and improve product quality.
- **Technologies Used**: Postman (API testing), HTML (basic functional mockup).
- **Date Created**: October 26, 2025

## Features
- **Test Cases**: Manual test scenarios for transaction creation, insufficient balance checks, and transaction history retrieval.
- **API Testing**: Simulated API requests using Postman for a mock Fintech API endpoint.
- **Functional Testing**: A simple HTML mockup to verify basic app functionality.

## Getting Started
### Prerequisites
- [Postman](https://www.postman.com/downloads/) for API testing.
- A text editor (e.g., Notepad++, VS Code).
- A web browser to view the HTML mockup.

### Installation
1. Clone the repository:
2.  Navigate to the project folder:
3.  Open `fintech_app.html` in a browser to view the mockup.
4. Import the Postman collection (if exported) or manually set up requests as described.

## Project Structure
- `test_cases.txt`: Contains manual test cases for the Fintech app.
- `test_results.txt`: Documents the results of executed tests.
- `fintech_app.html`: A basic HTML mockup for functional testing.

## Usage
1. **Review Test Cases**: Open `test_cases.txt` to see the defined test scenarios.
2. **Execute API Tests**:
- Use Postman to send requests to the mock API endpoint (`https://api.fintechapp.com/transaction`).
- Example POST request body: `{"user_id": "123", "amount": 100, "receiver_id": "456"}`.
- Example GET request: `https://api.fintechapp.com/transaction/history?user_id=123`.
- Note: This is a mock API; responses are simulated based on expected outcomes.
3. **Functional Test**: Open `fintech_app.html` in a browser to verify the mock interface.
4. **Document Results**: Update `test_results.txt` with actual outcomes.

## Limitations
- The API endpoint is a mock simulation due to the absence of a live server. Real-world testing would require integration with an actual API.
- This is a basic prototype to demonstrate testing concepts.

## Skills Demonstrated
- Creation of manual test cases and test plans.
- Execution and verification of API and functional tests.
- Basic knowledge of HTML, CSS, and API concepts (aligns with JTG's required skill set).
- Attention to detail and proactive problem-solving.

## Future Improvements
- Integrate with a real API for live testing.
- Add automated test scripts using tools like Selenium or JUnit.
- Expand test cases to cover edge cases and performance testing.

 


*Created with passion on October 26, 2025, at 09:59 PM IST.*
