# REQUIREMENTS TRACEABILITY MATRIX
## Sauce Demo - QA Portfolio

**Purpose:** Map requirements to test cases to ensure complete coverage

---

## TRACEABILITY OVERVIEW

| Requirement ID | Requirement | Test Cases | Coverage |
|---------------|-------------|------------|----------|
| REQ-001 | User Authentication | TC_LOGIN_001-007 | 100% ✅ |
| REQ-002 | Product Display | TC_INVENTORY_001, 006-007 | 100% ✅ |
| REQ-003 | Product Sorting | TC_INVENTORY_002-005 | 100% ✅ |
| REQ-004 | Add to Cart | TC_CART_001-002 | 100% ✅ |
| REQ-005 | Remove from Cart | TC_CART_003-005 | 100% ✅ |
| REQ-006 | Checkout Process | TC_CHECKOUT_001-005 | 100% ✅ |
| REQ-007 | Form Validation | TC_CHECKOUT_006-009 | 100% ✅ |

**Overall Coverage: 100%** (All requirements have test cases)

---

## DETAILED MAPPING

### REQ-001: User Authentication
**Description:** Users must be able to log in with valid credentials

| Test Case ID | Description | Status |
|-------------|-------------|--------|
| TC_LOGIN_001 | Valid login | ✅ Covered |
| TC_LOGIN_002 | Invalid username | ✅ Covered |
| TC_LOGIN_003 | Invalid password | ✅ Covered |
| TC_LOGIN_004 | Empty username | ✅ Covered |
| TC_LOGIN_005 | Empty password | ✅ Covered |
| TC_LOGIN_006 | Locked user | ✅ Covered |
| TC_LOGIN_007 | SQL injection | ✅ Covered |

---

### REQ-002: Product Display
**Description:** Users can view product list and details

| Test Case ID | Description | Status |
|-------------|-------------|--------|
| TC_INVENTORY_001 | View product list | ✅ Covered |
| TC_INVENTORY_006 | View details via name | ✅ Covered |
| TC_INVENTORY_007 | View details via image | ✅ Covered |

---

### REQ-003: Product Sorting
**Description:** Users can sort products by price and name

| Test Case ID | Description | Status |
|-------------|-------------|--------|
| TC_INVENTORY_002 | Sort price low-high | ✅ Covered |
| TC_INVENTORY_003 | Sort price high-low | ✅ Covered |
| TC_INVENTORY_004 | Sort name A-Z | ✅ Covered |
| TC_INVENTORY_005 | Sort name Z-A | ✅ Covered |

---

### REQ-004: Add to Cart
**Description:** Users can add products to shopping cart

| Test Case ID | Description | Status |
|-------------|-------------|--------|
| TC_CART_001 | Add from inventory page | ✅ Covered |
| TC_CART_002 | Add from detail page | ✅ Covered |

---

### REQ-005: Remove from Cart
**Description:** Users can remove products from cart

| Test Case ID | Description | Status |
|-------------|-------------|--------|
| TC_CART_003 | Remove from inventory | ✅ Covered |
| TC_CART_004 | Remove from detail page | ✅ Covered |
| TC_CART_005 | Remove from cart page | ✅ Covered |

---

### REQ-006: Checkout Process
**Description:** Users can complete purchase checkout

| Test Case ID | Description | Status |
|-------------|-------------|--------|
| TC_CHECKOUT_001 | Proceed to checkout | ✅ Covered |
| TC_CHECKOUT_002 | Enter valid info | ✅ Covered |
| TC_CHECKOUT_003 | View order overview | ✅ Covered |
| TC_CHECKOUT_004 | Complete order | ✅ Covered |
| TC_CHECKOUT_005 | View confirmation | ✅ Covered |

---

### REQ-007: Form Validation
**Description:** System validates required checkout fields

| Test Case ID | Description | Status |
|-------------|-------------|--------|
| TC_CHECKOUT_006 | Empty first name | ✅ Covered |
| TC_CHECKOUT_007 | Empty last name | ✅ Covered |
| TC_CHECKOUT_008 | Empty zip code | ✅ Covered |
| TC_CHECKOUT_009 | All fields empty | ✅ Covered |

---

## COVERAGE ANALYSIS

### By Module
- **Login:** 7/7 requirements covered (100%)
- **Inventory:** 7/7 requirements covered (100%)
- **Cart:** 5/5 requirements covered (100%)
- **Checkout:** 10/10 requirements covered (100%)

### By Priority
- **High Priority:** 100% covered
- **Medium Priority:** 100% covered
- **Low Priority:** 100% covered

---

*Matrix prepared by: Tayfun Yaman*  
*Date: January 14, 2026*
