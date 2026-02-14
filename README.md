# OpenCart Manual Testing Project – Admin Panel UI

This repository contains a manual UI testing project for the OpenCart Admin Panel.
The focus is on validating critical back-office functionality used by administrators
to manage orders and products.

Testing was performed using real admin workflows and realistic test data.
All test cases were executed manually and documented in a structured format.

---

## Project purpose

The goal of this project is to:

- Validate core admin panel functionality
- Ensure order management works correctly
- Ensure product management works correctly
- Verify data updates are reflected accurately in the system
- Document defects and results in a clear, professional way

This project is intended as a portfolio example of structured manual testing
for an admin/back-office application.

---

## System under test

- Application: OpenCart
- Area tested: Admin Panel (Back Office)
- Environment: Local OpenCart installation (XAMPP)
- User role: Admin

---

## Test scope

### In scope
- Admin login
- Order management
  - View order details
  - Update order status
- Product management
  - Add product
  - Edit product
  - Delete product

### Out of scope
- Storefront (customer UI)
- API testing
- Performance testing
- Security testing
- Configuration and settings outside orders/products

---

## Test approach

- Manual UI testing
- Step-by-step execution of predefined test cases
- Dynamic data usage where required (e.g. order IDs)
- Validation of:
  - visible UI messages
  - data accuracy
  - system feedback after actions
- All results documented with pass/fail status

---

## Documentation included

- **TEST_PLAN.md** – test objectives, scope, strategy
- **TEST_ROADMAP.md** – future test expansion
- **TRACEABILITY.md** – mapping between requirements and test cases
- **TEST_SUMMARY.md** – execution results and observations

---

## Author

**George Petre**  
Portfolio: https://georgempetre.github.io