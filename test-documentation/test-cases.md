# Test Cases

## Login

| ID | Test Case | Priority | Expected Result | Automation |
|---|---|---|---|---|
| TC-LOGIN-001 | Valid login | High | User is redirected to Products page | Yes |
| TC-LOGIN-002 | Invalid username | High | Error message is displayed | Yes |
| TC-LOGIN-003 | Invalid password | High | Error message is displayed | Yes |
| TC-LOGIN-004 | Empty username | High | Validation message is displayed | Yes |
| TC-LOGIN-005 | Empty password | High | Validation message is displayed | Yes |
| TC-LOGIN-006 | Empty credentials | Medium | Validation message is displayed | Yes |
| TC-LOGIN-007 | Locked user | High | Locked-user error is displayed | Yes |

## Products

| ID | Test Case | Priority | Expected Result | Automation |
|---|---|---|---|---|
| TC-PROD-001 | Verify products page | High | Products page is displayed | Yes |
| TC-PROD-002 | Verify product list | High | Products are displayed correctly | Yes |
| TC-PROD-003 | Sort products A-Z | Medium | Products are sorted A-Z | Yes |
| TC-PROD-004 | Sort products Z-A | Medium | Products are sorted Z-A | Yes |
| TC-PROD-005 | Sort by price low-high | Medium | Lowest price appears first | Yes |
| TC-PROD-006 | Sort by price high-low | Medium | Highest price appears first | Yes |
| TC-PROD-007 | Open product details | High | Correct product details are displayed | Yes |

## Shopping Cart

| ID | Test Case | Priority | Expected Result | Automation |
|---|---|---|---|---|
| TC-CART-001 | Add one product | High | Product appears in cart | Yes |
| TC-CART-002 | Add multiple products | High | Selected products appear in cart | Yes |
| TC-CART-003 | Remove product | High | Product is removed | Yes |
| TC-CART-004 | Verify cart quantity | Medium | Correct quantity is displayed | Yes |
| TC-CART-005 | Verify product price | High | Correct price is displayed | Yes |

## Checkout

| ID | Test Case | Priority | Expected Result | Automation |
|---|---|---|---|---|
| TC-CHECK-001 | Checkout with valid data | High | User proceeds to overview | Yes |
| TC-CHECK-002 | Empty first name | High | Validation message is displayed | Yes |
| TC-CHECK-003 | Empty last name | High | Validation message is displayed | Yes |
| TC-CHECK-004 | Empty postal code | High | Validation message is displayed | Yes |
| TC-CHECK-005 | Verify order summary | High | Correct products and prices are displayed | Yes |
| TC-CHECK-006 | Complete purchase | High | Order confirmation is displayed | Yes |

## Logout

| ID | Test Case | Priority | Expected Result | Automation |
|---|---|---|---|---|
| TC-LOGOUT-001 | Logout | High | User returns to login page | Yes |
| TC-LOGOUT-002 | Access application after logout | High | Authenticated page cannot be accessed | Yes |
