# SauceDemo – Checkout Test Cases

## Test Execution Summary

| Test ID | Test Scenario | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| TC-CHECKOUT-001 | Verify checkout with empty information fields | The system should prevent the user from proceeding and display a validation message indicating that First Name is required. | Error message displayed: "Error: First Name is required". The user remained on the checkout information page. | Pass |
| TC-CHECKOUT-002 | Verify checkout with empty Last Name | The system should prevent the user from proceeding and display a validation message indicating that Last Name is required. | Error message displayed: "Error: Last Name is required". | Pass |
| TC-CHECKOUT-003 | Verify checkout with empty Postal Code | The system should prevent the user from proceeding and display a validation message indicating that Postal Code is required. | Error message displayed: "Error: Postal Code is required". | Pass |
| TC-CHECKOUT-004 | Verify checkout with valid information | The system should accept valid customer information and navigate to the Checkout Overview page, displaying the correct product details. | The Checkout Overview page opened successfully. Sauce Labs Backpack was displayed with the correct price ($29.99). | Pass |
| TC-CHECKOUT-005 | Verify successful order completion | The system should display an order confirmation message after clicking Finish. | The Checkout Complete page displayed the message: "Thank you for your order! Your order has been dispatched, and will arrive just as fast as the pony can get there!" | Pass |