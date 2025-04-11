# 📱 Meesho Mobile Application - QA Testing

## Overview
This repository contains the Quality Assurance (QA) documentation and summary for the manual efforts on the **Meesho Mobile Application**. The goal is to ensure that the application is stable, reliable, and meets user and business requirements before going live.

---

## 🎯 Objective
To validate the functionality, usability, performance, security, and compatibility of the Meesho mobile app on Android and iOS platforms. The objective is to identify and eliminate defects prior to release.

---

## 📦 Scope

### ✅ In-Scope
- User Authentication: Mobile OTP, Google, Facebook logins
- Product Browsing, Search, Cart, and Checkout
- Payment Gateway Integration (UPI, Cards, Wallets)
- Order Tracking and Address Management
- Push Notifications & In-App Promotions
- Compatibility Testing on Android & iOS Devices

### ❌ Out-of-Scope
- Backend services testing
- API load testing (handled by backend team)

---

## 🧪 Test Strategy

### Test Methodology
- **Manual Testing**: UI/UX, exploratory, and regression
- **Agile**: Sprint-based iterative testing and execution

### Test Approach
- Create test scenarios and cases based on user stories
- Execute in staging environment
- Log defects in Jira and participate in triage meetings
- Perform regression testing before each release

---

## ⚙️ Tools & Technologies
- **Defect Tracking**: Jira
- **Device Coverage**: BrowserStack (Cloud Device Farm)
- **Test Case Management**: Zephyr / Excel

---

## 🚪 Entry & Exit Criteria

### Entry Criteria
- Functional requirements are finalized
- APIs are integrated and stable
- QA environment and data are available

### Exit Criteria
- All critical test cases executed
- No critical/high-severity bugs remain
- Final test summary report delivered

---

## 🐛 Defect Management
- All issues are logged in Jira
- Severity and priority assigned to each defect
- Retesting done post-fix confirmation
- Daily triage meetings for defect prioritization

---

## ⏱️ Test Schedule

| Phase                   | Duration          |
|------------------------|-------------------|
| Test Planning           | 1 Days            |
| Test Case Design        | 1 Days            |
| Test Case Review        | 1 Days            |
| Sprint Test Execution   |1 Days |
| Regression Testing      | 1 Days/Sprint     |
| UAT Support             | As scheduled      |

---

## 👤 Roles & Responsibilities

- Design and execute manual test cases
- Report defects with reproduction steps and screenshots
- Communicate daily test progress and risks
- Participate in sprint ceremonies
- Collaborate with developers for faster bug resolution

---

## 📈 Test Summary Report

**Date:** April 10, 2025  
**Tested By:** Rohit Chouhan  
**Environment:** Staging  
**Platform:** Android / iOS  
**Test Type:** Functional (Manual Testing)

### ✅ Test Case Summary

| Module                  | Total Cases | Passed | Status  |
|-------------------------|-------------|--------|---------|
| Login                   | 6           | 6      | ✅ Passed |
| Product Search          | 15          | 15     | ✅ Passed |
| Add to Cart             | 15          | 15     | ✅ Passed |
| Price Detail Verification | 10        | 10     | ✅ Passed |
| Payment Functionality   | 13          | 13     | ✅ Passed |
| Add Delivery Address    | 15          | 15     | ✅ Passed |

### 📊 Summary

- **Total Executed:** 74  
- **Total Passed:** 74  
- **Total Failed:** 0  
- **Overall Status:** ✅ **All test cases passed successfully**

### 📝 Remarks
- All core functionalities worked as expected
- No critical or high-severity bugs were found
- Application is stable and ready for deployment

---

## 📁 Deliverables
- ✅ Test Plan Document  
- ✅ Test Cases and Scenarios  
- ✅ Test Summary Report  
- ✅ Defect Reports 
---

## 📋 Templates Used
- Test Case Template (Excel / Zephyr)
- Daily QA Status Template
- Final Test Summary Report

---

## 📌 Author
**Rohit Chouhan**  
QA Engineer | Manual  
Tested the Meesho Mobile Application on both Android and iOS platforms using a blend of manual  practices.

---
