# TEST PLAN
## Sauce Demo - QA Portfolio Project

**Project:** Manual Testing Portfolio  
**Application:** Sauce Demo (https://www.saucedemo.com)  
**Version:** 001 
**Prepared by:** Tayfun Yaman  
**Date:** January 13, 2026

---

## 1. INTRODUCTION

### 1.1 Purpose
This test plan outlines the approach for manually testing Sauce Demo 
application to demonstrate QA testing skills for portfolio purposes.

### 1.2 Objectives
- Validate core e-commerce functionality
- Identify bugs and document findings
- Demonstrate systematic testing approach
- Build professional QA portfolio

---

## 2. SCOPE

### 2.1 In Scope
✅ Login functionality  
✅ Product inventory browsing  
✅ Sorting and filtering  
✅ Shopping cart operations  
✅ Checkout process  
✅ Form validations  
✅ Basic security awareness (SQL injection)  
✅ Performance observation  

### 2.2 Out of Scope
❌ Hamburger menu navigation  
❌ Footer links (social media, external)  
❌ About page content  
❌ Responsive design / Mobile testing  
❌ Cross-browser compatibility (Chrome only)  
❌ API testing  
❌ Database testing  

**Justification:** Portfolio focuses on core purchase flow to demonstrate 
essential QA skills within reasonable time constraints.

---

## 3. TEST STRATEGY

### 3.1 Test Levels
- **Functional Testing** - Primary focus
- **Security Testing** - Basic awareness level
- **Performance Testing** - Observation only

### 3.2 Test Types
- **Positive Testing** - Happy path scenarios
- **Negative Testing** - Invalid inputs, error handling
- **Boundary Testing** - Edge cases (empty fields)
- **Cross-User Testing** - Multiple user accounts

### 3.3 Test Approach
1. Manual test execution
2. Exploratory testing for bug discovery
3. Systematic test case execution
4. Bug documentation with evidence

---

## 4. TEST ENVIRONMENT

### 4.1 Application
- **URL:** https://www.saucedemo.com
- **Environment:** Production (public demo)
- **Access:** No authentication required

### 4.2 Test Platform
- **Browser:** Chrome 143.0
- **OS:** Mac OS 26.0.1
- **Screen Resolution:** 2560x1440 (laptop)
- **Tools:** Chrome DevTools, Google Sheets

### 4.3 Test Users
- `standard_user` - Baseline functionality
- `problem_user` - Known UI issues
- `performance_glitch_user` - Performance testing
- `error_user` - Error scenarios
- `locked_out_user` - Negative testing

---

## 5. TEST DELIVERABLES

### 5.1 Documents
- ✅ Test cases (Excel format)
- ✅ Test execution results
- ✅ Bug reports with screenshots
- ✅ Test summary report
- ✅ This test plan

### 5.2 Artifacts
- Screenshots of bugs
- Screen recordings where applicable
- Performance metrics (LCP)

---

## 6. TEST SCHEDULE

| Phase | Duration | Dates |
|-------|----------|-------|
| Test Planning | 0.5 day | Jan 13 AM |
| Test Case Design | 0.5 day | Jan 13 PM |
| Test Execution | 1.5 days | Jan 13-14 |
| Bug Documentation | 0.5 day | Jan 14 |
| Reporting | 0.5 day | Jan 14 |
| **Total** | **3 days** | **Jan 13-15** |

---

## 7. ENTRY & EXIT CRITERIA

### 7.1 Entry Criteria
✅ Application is accessible  
✅ Test environment is available  
✅ Test cases are prepared  
✅ Test user credentials confirmed  

### 7.2 Exit Criteria
✅ All test cases executed  
✅ All bugs documented  
✅ Test summary report completed  
✅ Evidence collected (screenshots)  
✅ 100% test case coverage achieved  

---

## 8. TEST CASES

### 8.1 Test Case Distribution

| Module | Test Cases | Priority |
|--------|-----------|----------|
| Login | 7 | High |
| Inventory | 7 | High |
| Cart | 5 | High |
| Checkout | 10 | High |
| **Total per user** | **29** | - |

**Total across 4 users:** 116 test cases

### 8.2 Test Prioritization
- **High Priority:** Login, Add to cart, Checkout
- **Medium Priority:** Sorting, Product details
- **Low Priority:** Field validations, edge cases

---

## 9. DEFECT MANAGEMENT

### 9.1 Bug Severity Levels
- **Critical:** Application crashes, data loss
- **High:** Major functionality broken
- **Medium:** Feature works but with issues
- **Low:** Minor UI issues, typos

### 9.2 Bug Workflow
1. Bug identified during testing
2. Screenshot/recording captured
3. Bug report created with steps
4. Bug added to tracking sheet
5. Linked to related test case

---

## 10. RISKS & ASSUMPTIONS

### 10.1 Risks
| Risk | Impact | Mitigation |
|------|--------|------------|
| Limited time (3 days) | Medium | Focus on core flows |
| No test environment control | Low | Document as-is |
| Single browser testing | Low | Note in limitations |

### 10.2 Assumptions
- Application is stable and accessible
- Test data is available
- User credentials don't change
- No test automation available yet

---

## 11. ROLES & RESPONSIBILITIES

| Role | Responsibility | Name |
|------|---------------|------|
| Test Lead | Planning, execution, reporting | Tayfun Yaman |
| Tester | Test execution, bug reporting | Tayfun Yaman |
| Reviewer | Portfolio review (self) | Tayfun Yaman |

*Note: Solo project for portfolio purposes*

---

## 12. CONCLUSION

This test plan provides a structured approach to testing Sauce Demo 
application. The focus is on demonstrating core QA skills including 
test planning, execution, and documentation.

**Success Criteria:**
- Complete test coverage of core functionality
- Identify and document significant bugs
- Professional documentation quality
- Portfolio-ready deliverables

---

## 13. APPROVAL

| Role | Name | Signature | Date |
|------|------|-----------|------|
| Prepared by | [Tayfun Yaman] | | Jan 13, 2026 |

---

*This is a personal portfolio project. Approval section included for 
demonstration of professional documentation standards.*