# SauceDemo – Manual Test Cases

## 1. Test Case Overview

Application: https://www.saucedemo.com/
Testing Type: Manual Testing
Test Environment: Web Browser
Test Status: Not Executed

Objective: Verify the functionality of login, product listing, shopping cart and checkout.
---
## 2. Login Testing

### TC_LOGIN_001 – Login with valid credentials
Priority: High
Type: Positive

Steps:
1. Open the application.
2. Enter valid demo username and password.
3. Click Login.
   
Expected Result:
User should log in successfully and see the inventory page.

Status: Not Run

### TC_LOGIN_002 – Login with invalid username
Priority: High
Type: Negative

Steps:
1. Open the application.
2. Enter an invalid username.
3. Enter a valid demo password.
4. Click Login.

Expected Result:
An appropriate error message should be displayed.

Status: Not Run

### TC_LOGIN_003 – Login with invalid password
Priority: High
Type: Negative

Steps:
1. Open the application.
2. Enter a valid demo username.
3. Enter an incorrect password.
4. Click Login.

Expected Result:
Login should fail and an error message should be displayed.

Status: Not Run

### TC_LOGIN_004 – Login without username
Priority: High
Type: Negative

Steps:
1. Open the application.
2. Leave username empty.
3. Enter a password.
4. Click Login.

Expected Result:
Validation message should be displayed for the missing username.

Status: Not Run

### TC_LOGIN_005 – Login without password
Priority: High
Type: Negative

Steps:
1. Open the application.
2. Enter a valid demo username.
3. Leave password empty.
4. Click Login.

Expected Result:
Validation message should be displayed for the missing password.

Status: Not Run

-------------------------------------------------------------------------

## 3. Product Inventory Testing

### TC_PRODUCT_001 – Verify inventory page
Priority: High
Type: Functional

Steps:
1. Login successfully.
2. Open the inventory page.

Expected Result:
Product listings, names, prices and images should be displayed correctly.

Status: Not Run

### TC_PRODUCT_002 – View product details
Priority: Medium
Type: Functional

Steps:
1. Open the inventory page.
2. Select a product name.

Expected Result:
The selected product details page
should be displayed.

Status: Not Run

### TC_PRODUCT_003 – Navigate back to inventory
Priority: Medium
Type: Functional

Steps:
1. Open a product details page.
2. Click Back to Products.

Expected Result:
User should return to the inventory page.

Status: Not Run

### TC_PRODUCT_004 – Sort products by name A to Z
Priority: Medium
Type: Functional

Steps:
1. Open the inventory page.
2. Select Name A to Z from the sorting option.

Expected Result:
Products should appear in alphabetical order.

Status: Not Run

### TC_PRODUCT_005 – Sort products by name Z to A
Priority: Medium
Type: Functional

Steps:
1. Open the inventory page.
2. Select Name Z to A.

Expected Result:
Products should appear in reverse
alphabetical order.

Status: Not Run

### TC_PRODUCT_006 – Sort products by price low to high
Priority: Medium
Type: Functional

Steps:
1. Open the inventory page.
2. Select Price low to high.

Expected Result:
Products should be displayed from lowest to highest price.

Status: Not Run

### TC_PRODUCT_007 – Sort products by price high to low
Priority: Medium
Type: Functional

Steps:
1. Open the inventory page.
2. Select Price high to low.

Expected Result:
Products should be displayed from highest to lowest price.

Status: Not Run

---

## 4. Shopping Cart Testing

### TC_CART_001 – Add one product to cart
Priority: High
Type: Functional

Steps:
1. Open the inventory page.
2. Click Add to cart for one product.

Expected Result:
Product should be added to the cart. Cart count should increase by one.

Status: Not Run

### TC_CART_002 – Add multiple products to cart
Priority: High
Type: Functional

Steps:
1. Select multiple products.
2. Click Add to cart for each product.

Expected Result:
All selected products should be added and the cart count should be updated.

Status: Not Run

### TC_CART_003 – Remove product from inventory
Priority: Medium
Type: Functional

Steps:
1. Add a product to the cart.
2. Click Remove on the inventory page.

Expected Result:
Product should be removed from the cart.
Cart count should be updated.

Status: Not Run

### TC_CART_004 – Verify cart contents
Priority: High
Type: Functional

Steps:
1. Add one or more products.
2. Open the shopping cart.

Expected Result:
Cart should display the selected products with correct names and prices.

Status: Not Run

### TC_CART_005 – Remove product from cart
Priority: Medium
Type: Functional

Steps:
1. Open the shopping cart.
2. Click Remove for a selected product.

Expected Result:
Selected product should be removed from the cart.

Status: Not Run

### TC_CART_006 – Continue shopping
Priority: Low
Type: Functional

Steps:
1. Open the shopping cart.
2. Click Continue Shopping.

Expected Result:
User should return to the inventory page.

Status: Not Run

---

## 5. Checkout Testing

### TC_CHECKOUT_001 – Proceed with valid customer details
Priority: High
Type: Positive

Steps:
1. Add a product to the cart.
2. Click Checkout.
3. Enter valid first name, last name
   and postal code.
4. Click Continue.

Expected Result:
User should proceed to the checkout overview page.

Status: Not Run

### TC_CHECKOUT_002 – Checkout without first name
Priority: High
Type: Negative

Steps:
1. Add a product to the cart.
2. Click Checkout.
3. Leave first name empty.
4. Enter other required details.
5. Click Continue.

Expected Result:
Validation message should be displayed.

Status: Not Run

### TC_CHECKOUT_003 – Checkout without last name
Priority: High
Type: Negative

Steps:
1. Add a product to the cart.
2. Click Checkout.
3. Enter first name.
4. Leave last name empty.
5. Enter postal code and continue.

Expected Result:
Validation message should be displayed.

Status: Not Run

### TC_CHECKOUT_004 – Checkout without postal code
Priority: High
Type: Negative

Steps:
1. Add a product to the cart.
2. Click Checkout.
3. Enter first and last name.
4. Leave postal code empty.
5. Click Continue.

Expected Result:
Validation message should be displayed.

Status: Not Run

### TC_CHECKOUT_005 – Verify order summary
Priority: High
Type: Functional

Steps:
1. Add products to the cart.
2. Complete customer information.
3. Navigate to the checkout overview.

Expected Result:
Selected products, item prices, subtotal, tax and total should be displayed correctly.

Status: Not Run

### TC_CHECKOUT_006 – Complete an order
Priority: High
Type: Positive

Steps:
1. Complete checkout with valid details.
2. Review the order summary.
3. Click Finish.

Expected Result:
Order confirmation message should be displayed successfully.

Status: Not Run

---

## 6. Logout Testing

### TC_LOGOUT_001 – Logout from application
Priority: High
Type: Functional

Steps:
1. Login successfully.
2. Open the navigation menu.
3. Click Logout.

Expected Result:
User should be logged out and returned to the login page.

Status: Not Run

---

## 7. Test Execution Summary

Total Test Cases: 25
Executed: 0
Passed: 0
Failed: 0
Blocked: 0
Not Run: 25
Execution Status: Pending

Note: Actual test results will be updated after executing each test case.
