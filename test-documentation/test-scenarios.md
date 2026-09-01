# Test Scenarios

## TS-001 — Login

Verify that users can successfully authenticate and that invalid credentials are handled correctly.

### Scenarios

- Login with valid credentials
- Login with invalid username
- Login with invalid password
- Login with empty username
- Login with empty password
- Login with empty credentials
- Login with locked user

---

## TS-002 — Product Browsing

Verify that users can browse and interact with available products.

### Scenarios

- Verify products page
- Verify product list
- Sort products alphabetically
- Sort products by price
- Open product details

---

## TS-003 — Shopping Cart

Verify that users can add, view and remove products.

### Scenarios

- Add a single product
- Add multiple products
- Remove a product
- Verify cart quantity
- Verify product price
- Continue shopping

---

## TS-004 — Checkout

Verify that users can complete the checkout process.

### Scenarios

- Checkout with valid customer information
- Checkout with missing first name
- Checkout with missing last name
- Checkout with missing postal code
- Verify order summary
- Complete purchase
- Cancel checkout

---

## TS-005 — Logout

Verify that users can securely log out.

### Scenarios

- Logout from the application
- Attempt to access authenticated pages after logout
