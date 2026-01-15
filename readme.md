# 🧪 Sauce Demo - QA Testing Portfolio

> Manual testing portfolio demonstrating functional testing, bug detection, 
> and documentation skills for Junior QA role.55

## 📋 Project Overview

**Application Under Test:** [Sauce Demo](https://www.saucedemo.com)  
**Testing Type:** Manual Functional Testing  
**Duration:** 2 days  
**Total Test Cases:** 116  
**Bugs Found:** 19

---

## 🎯 Objectives

- Demonstrate test case design and execution skills
- Show bug detection and reporting abilities  
- Practice cross-user testing methodology
- Build professional QA documentation

---

## 🧑‍💻 Test Coverage

### Modules Tested
✅ **Login Module** - Authentication and validation  
✅ **Inventory Module** - Product display and sorting  
✅ **Cart Module** - Add/remove items functionality  
✅ **Checkout Module** - Purchase flow validation  

### User Types Tested
- `standard_user` - Baseline functionality (✅ 100% pass)
- `problem_user` - UI/UX issues (❌ 31% pass, 11 bugs)
- `performance_glitch_user` - Performance testing (⚠️ 27x slower)
- `error_user` - Error handling (❌ 59% pass, 7 bugs)

---

## 📊 Test Results Summary
```
Total Tests Executed: 116
├─ Passed:   84 (72%)
├─ Failed:   26 (22%)  
└─ Blocked:  14 (12%)

Bugs Found: 19
├─ Critical: 4
├─ High:     9
└─ Medium:   6
```

---

## 📁 Repository Structure
```
sauce-demo-qa-portfolio/
├── README.md
├── test-cases/
│   └── TEST_CASES.md              # 📊 Links to all test case sheets
├── bug-reports/
│   ├── BUG_REPORTS.md             # 🐛 Link to bug tracking sheet
│   └── evidence/                   # 📸 Screenshots & videos
├── documentation/
│   ├── test_summary_report.md
│   ├── test_plan.md
│   ├── user_comparison_analysis.md
│   ├── scope_document.md
│   └── traceability_matrix.md
```

---

## 🔗 QUICK LINKS

### Test Cases (Google Sheets)
📊 **[All Test Cases](test-cases/TEST_CASES.md)** - Links to all 4 user test sheets

### Bug Reports (Google Sheets)
🐛 **[All Bugs](bug-reports/BUG_REPORTS.md)** - Complete bug tracking sheet

### Documentation
📄 **[Test Summary Report](documentation/test_summary_report.md)**  
📄 **[User Comparison Analysis](documentation/user_comparison_analysis.md)**  
📄 **[Test Plan](documentation/test_plan.md)**  
📄 **[Scope Document](documentation/scope_document.md)**  
📄 **[Traceability Matrix](documentation/traceability_matrix.md)**

---

## 🐛 Key Bugs Found

### Critical Issues
- **BUG_012-015:** Sorting feature crashes for error_user
- **BUG_019:** Finish button non-functional in checkout

### High Priority  
- **BUG_008-009:** Add to cart fails for 50% of products
- **BUG_018:** Checkout validation bypassed for error_user

### Performance Issues
- **BUG_011:** 27x slower page load (5.49s vs 0.20s baseline)

**🔗 [View All Bugs](bug-reports/BUG_REPORTS.md)**

---

## 🛠️ Skills Demonstrated

- ✅ Test case design (116 test cases)
- ✅ Test execution and tracking
- ✅ Bug identification and reporting
- ✅ Cross-browser testing
- ✅ Performance awareness
- ✅ Security testing basics (SQL injection)
- ✅ Professional documentation
- ✅ Google Sheets for test management

---

## 📚 Testing Approach

1. **Test Planning** - Defined scope and test strategy
2. **Test Design** - Created comprehensive test cases
3. **Test Execution** - Systematic testing across users
4. **Bug Reporting** - Detailed defect documentation
5. **Test Summary** - Results analysis and recommendations

---

## 🔧 Tools & Technologies

- **Testing:** Manual testing (Chrome DevTools)
- **Documentation:** Google Sheets, Markdown
- **Performance:** Chrome Lighthouse (LCP metrics)
- **Bug Tracking:** Google Sheets
- **Evidence:** Screenshots, screen recordings
- **Version Control:** Git/GitHub

---

## 📈 Future Enhancements

- [ ] Automation with Selenium/Cypress
- [ ] API testing with Postman
- [ ] Mobile responsive testing
- [ ] Accessibility testing (WCAG)
- [ ] CI/CD integration
- [ ] Test management tool (TestRail/Zephyr)

---

## 💼 About This Portfolio

This project was created to demonstrate my QA testing skills as I transition 
into a professional QA role. I completed online courses in software testing 
fundamentals and ISTQB Foundation Level concepts, and created this portfolio 
to apply those learnings practically.

**Learning Resources:**
- ISTQB Foundation Level training
- Online QA testing courses (Udemy, Coursera)
- Self-study: Test design techniques
- Practice: Sauce Demo test automation playground

---

## 📧 Contact

**[Your Name]**  
📧 Email: your.email@example.com  
💼 LinkedIn: [linkedin.com/in/your-profile](https://linkedin.com/in/your-profile)  
🐙 GitHub: [@your-username](https://github.com/your-username)

---

## 🙏 Acknowledgments

- [Sauce Labs](https://saucelabs.com) for providing Sauce Demo
- ISTQB for testing standards and best practices
- Online QA community for guidance and support

---

## 📝 NOTES FOR REVIEWERS

### Google Sheets Access
All test cases and bug reports are maintained in Google Sheets with 
"Anyone with the link can view" permissions. This allows:
- Easy collaboration and review
- Real-time updates
- Familiar spreadsheet interface
- Professional test management simulation

### Evidence Files
Screenshots and screen recordings are stored in this repository under 
`bug-reports/evidence/` for direct access and reference.

---

⭐ **If you find this portfolio helpful, please consider giving it a star!**

---

*Last updated: January 2026*
