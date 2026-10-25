
# Login Test Cases

## Test Objective
Verify that the login page handles valid and invalid login attempts correctly.

## Test Environment
- Application: SauceDemo
- Test Type: Manual Testing
- Browser: [Write your browser name]
- Date: [Write the test date]

## Test Cases

| Test Case ID | Scenario | Preconditions | Test Steps | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|
| TC-LOGIN-001 | Login with valid credentials | Login page is open | 1. Enter a valid username. 2. Enter the matching password. 3. Click Login. | standard_user and the password displayed on SauceDemo | User should be redirected to the Products page. | Products page displayed after login. | Pass |

| TC-LOGIN-002 | Login with empty username and password | Login page is open | 1. Leave username empty. 2. Leave password empty. 3. Click Login. | Username: empty; Password: empty | An appropriate validation message should appear and login should be prevented. | Epic sadface: Username is required | Pass |

| TC-LOGIN-003 | Login with empty password | Login page is open | 1. Enter a valid username. 2. Leave password empty. 3. Click Login. | Username: standard_user; Password: empty | A validation message should appear and login should be prevented. | Epic sadface: Password is required | Pass |

| TC-LOGIN-004 | Login with invalid password | Login page is open | 1. Enter a valid username. 2. Enter an incorrect password. 3. Click Login. | Username: standard_user; Password: wrongpassword123 | Login should be prevented and an appropriate error message should appear. | Epic sadface: Username and password do not match any user in this service | Pass |

| TC-LOGIN-005 | Login with invalid username | Login page is open | 1. Enter an invalid username. 2. Enter the valid password displayed on SauceDemo. 3. Click Login. | Username: wrong_user_123; Password: valid SauceDemo password | Login should be prevented and an appropriate error message should appear. | Epic sadface: Username and password do not match any user in this service | Pass |

