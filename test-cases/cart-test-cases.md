# SauceDemo – Cart Test Cases

## Test Execution Summary

| Test ID | Test Scenario | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| TC-CART-001 | Verify adding a product to the cart | The Add to cart button should change to Remove, the cart badge should display 1, and the product listing should remain visible. | The button changed to Remove, the cart badge displayed 1, and all six products remained visible. | Pass |
| TC-CART-002 | Verify product details in the cart | The cart should display the correct product name, price, and quantity. | Sauce Labs Backpack was displayed with the correct name, price ($29.99), and quantity (1). | Pass |
| TC-CART-003 | Verify removing a product from the cart | The selected product should be removed from the cart, and the cart badge should disappear when the cart becomes empty. | Sauce Labs Backpack was removed from the cart, and the cart became empty. | Pass |