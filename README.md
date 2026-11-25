# Manual Testing Project – ShopSphere

End-to-end manual testing documentation for the **ShopSphere** e-commerce web application ([Practice Software Testing](https://practicesoftwaretesting.com)).

## Scope of Testing
Testing focused on five core modules against defined business rules:
* **Login & Registration:** Field validations, password rules, and duplicate email checks.
* **Product Search:** Keyword matching (case-sensitivity, special characters) and product pricing.
* **Shopping Cart:** Item management, stock limits, and subtotal calculations.
* **Coupon Application:** Code validation, minimum cart value rules, and discount math *(skipped if unavailable in build)*.
* **Checkout & Payment:** Order placement, address validation, payment failures, and duplicate submission prevention.

## Repository Structure
```text
manual-testing-project/
├── README.md
├── Test Scanarios.xlsx        # High-level test scenarios across all 5 modules
├── Module_wise-testcases.xlsx # Detailed test cases with steps, test data, and statuses
├── Bug Report.xlsx            # Logged defects with severity, priority, and reproduction steps
├── Test Report.xlsx           # Final test execution summary and metrics
└── Bug screenShots/           # Visual evidence for reported defects
