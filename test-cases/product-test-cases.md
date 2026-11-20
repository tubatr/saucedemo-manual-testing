# Product Test Cases

## Test Objective
To verify product listing information and product sorting functionality.

## Test Environment
- Application: SauceDemo
- Browser: Microsoft Edge
- Test Account: standard_user

## Test Cases

| Test Case ID | Test Scenario | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| TC-PRODUCT-001 | Verify product listing information | All six products should display their correct names, prices, images and descriptions. | All six products were displayed with their names, prices, images and descriptions. | Pass |
| TC-PRODUCT-002 | Verify product sorting by Name (Z to A) | Products should be sorted alphabetically in descending order. | The first product was Test.allTheThings() T-Shirt (Red), and the last product was Sauce Labs Backpack. | Pass |
| TC-PRODUCT-003 | Verify product sorting by Name (A to Z) | Products should be sorted alphabetically in ascending order. | The first product was Sauce Labs Backpack, and the last product was Test.allTheThings() T-Shirt (Red). | Pass |