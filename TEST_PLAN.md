# Test Plan — OpenCart Admin Panel Manual UI Testing

## 1. Objective

Define the scope, approach, and execution strategy for manual UI testing
of the OpenCart Admin Panel.

The goal is to confirm that critical admin operations work correctly
and that system changes are applied as expected.

---

## 2. Scope

### In scope
- Admin authentication
- Order management:
  - viewing order details
  - updating order status
- Product management:
  - adding products
  - editing products
  - deleting products

### Out of scope
- Customer storefront
- API testing
- Performance and load testing
- Security testing

---

## 3. Test strategy

- Execute manual test cases based on real admin workflows
- Use dynamic data where applicable (e.g. order IDs from table)
- Validate system feedback via:
  - success messages
  - updated table values
  - correct data persistence
- Record pass/fail results for each test case

---

## 4. Test environment

- Application: OpenCart
- Area: Admin Panel
- Environment: Local (XAMPP)
- Browser: Desktop browser
- User role: Admin

---

## 5. Entry criteria

- Admin panel accessible
- Valid admin credentials available
- Test data present (orders and products)

---

## 6. Exit criteria

- All planned test cases executed
- Results recorded
- Any issues documented

---

## 7. Deliverables

- Manual test cases
- Test execution results
- Test summary and traceability matrix


## 8. Risks and mitigations

Local environment differs from production
Results may not fully reflect real user behaviour.
Mitigation: Clearly document environment limits and treat findings as functional validation, not production benchmarks.

Browser-specific UI differences
Layout or behaviour may vary across browsers.
Mitigation: Execute the same scenarios on Chrome, Firefox, and Edge and record any inconsistencies separately.
