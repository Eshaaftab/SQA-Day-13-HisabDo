# 🚀 Day 13 – Main Capstone Project

## HisabDo – Authentication & User Experience Testing

**Track:** Software Quality Assurance (SQA)
**Project:** HisabDo
**Intern:** Esha Tur Razia
**Day:** 13
**Testing Focus:** Authentication, Functional Testing & User Experience

---

## 📌 Project Overview

Day 13 of the HisabDo SQA Capstone Project focused on **Authentication Testing and User Experience (UX) Testing**.

The objective was to evaluate the reliability and usability of the HisabDo mobile application and website, with particular focus on:

* Login
* Registration
* Password validation
* Session handling
* Navigation
* Form validation
* Error handling
* Overall user experience

Testing was performed using positive, negative, boundary, validation, functional, and navigation testing techniques.

---

## 🎯 Objectives

* Verify login functionality.
* Test user registration.
* Validate password requirements.
* Test session and logout behavior.
* Verify navigation between authentication screens.
* Test input validation and error handling.
* Identify reproducible defects.
* Evaluate the overall UX of the application and website.

---

# 📱 Mobile App Testing

A total of **20 test cases** were executed on the HisabDo mobile application.

### Mobile Test Execution Summary

| Metric           | Result |
| ---------------- | -----: |
| Total Test Cases |     20 |
| Passed           |     13 |
| Failed           |      7 |
| Pass Rate        |    65% |
| Fail Rate        |    35% |

### Mobile Testing Areas

* Login
* Registration
* Password Validation
* Forgot Password
* Session Handling
* Logout
* Authentication Navigation
* Input Validation

---

# 🌐 Website Testing

A total of **15 test cases** were executed on the HisabDo website.

### Website Test Execution Summary

| Metric           | Result |
| ---------------- | -----: |
| Total Test Cases |     15 |
| Passed           |     10 |
| Failed           |      5 |
| Pass Rate        | 66.67% |
| Fail Rate        | 33.33% |

### Website Testing Areas

* Website Navigation
* Forms
* Input Validation
* Contact
* Support
* Page Navigation
* Error Handling

---

# 📊 Overall Test Execution

| Platform   | Total Test Cases | Passed | Failed |  Pass Rate |
| ---------- | ---------------: | -----: | -----: | ---------: |
| Mobile App |               20 |     13 |      7 |        65% |
| Website    |               15 |     10 |      5 |     66.67% |
| **Total**  |           **35** | **23** | **12** | **65.71%** |

---

# 🐞 Bug Reports

During testing, several reproducible issues were identified.

| Bug ID  | Platform | Module          | Bug Description                                            | Severity | Status |
| ------- | -------- | --------------- | ---------------------------------------------------------- | -------- | ------ |
| BUG-001 | Mobile   | Registration    | Duplicate accounts can be created using the same email     | High     | Open   |
| BUG-002 | Mobile   | Registration    | Invalid email format is accepted                           | Medium   | Open   |
| BUG-003 | Mobile   | Registration    | Name field accepts numbers and special characters          | Medium   | Open   |
| BUG-004 | Mobile   | Password        | Weak password such as `123456` is accepted                 | High     | Open   |
| BUG-005 | Mobile   | Forgot Password | Password recovery flow does not complete successfully      | High     | Open   |
| BUG-006 | Mobile   | Authentication  | Registration and sign-in behavior is inconsistent          | High     | Open   |
| BUG-007 | Website  | Forms           | Invalid email is accepted                                  | Medium   | Open   |
| BUG-008 | Website  | Forms           | Phone field accepts alphabetic characters                  | Medium   | Open   |
| BUG-009 | Website  | File Upload     | Unsupported file types are accepted                        | Medium   | Open   |
| BUG-010 | Website  | Support         | Footer support/email action does not open the email client | Low      | Open   |
| BUG-011 | Website  | Contact         | Contact email/support button is not clickable              | Medium   | Open   |
| BUG-012 | Website  | Careers         | Open Roles section is empty                                | Low      | Open   |

---

# 🎨 UX Review

## Usability

The application provides a relatively simple interface and its major features are understandable. However, some validation and authentication issues negatively affect the overall user experience.

## Navigation

Navigation between major sections is generally understandable. Authentication-related navigation should be further improved to provide a smoother and more consistent user journey.

## Authentication Experience

Authentication requires improvement due to issues related to registration, password validation, duplicate accounts, and password recovery.

## Form Experience

Some fields accept invalid or unexpected input. Stronger client-side and server-side validation should be implemented.

## Error Handling

Error handling should provide clearer and more meaningful messages so users can understand what went wrong and how to resolve the issue.

## Overall UX Assessment

| UX Area                 | Assessment                      |
| ----------------------- | ------------------------------- |
| Usability               | Good                            |
| Navigation              | Good                            |
| Login Experience        | Good                            |
| Registration Experience | Needs Improvement               |
| Password Validation     | Needs Improvement               |
| Forgot Password         | Poor                            |
| Form Validation         | Needs Improvement               |
| Error Handling          | Needs Improvement               |
| Visual Experience       | Good                            |
| Overall UX              | Good with areas for improvement |

---

# 💡 Recommended Improvements

1. Implement strong password validation and password-strength requirements.
2. Prevent duplicate account registration.
3. Validate email addresses properly.
4. Restrict name fields to appropriate characters.
5. Improve the Forgot Password workflow.
6. Provide clear and descriptive error messages.
7. Add proper validation to phone and other input fields.
8. Restrict unsupported file uploads.
9. Fix non-clickable contact/support actions.
10. Perform additional cross-device and responsive testing.
11. Improve consistency between registration and login flows.
12. Conduct regression testing after bug fixes.

---

# 🧪 Testing Techniques Used

The following testing techniques were used during Day 13:

* Positive Testing
* Negative Testing
* Boundary Value Testing
* Input Validation Testing
* Functional Testing
* Navigation Testing
* Error Handling Testing
* Session Testing
* Usability Testing
* UX Evaluation

---

# 📁 Deliverables

This repository contains the following Day 13 deliverables:

* 📱 Mobile App Test Cases
* 🌐 Website Test Cases
* 📊 Test Execution Report
* 🐞 Bug Reports
* 🎨 UX Review
* 📋 Testing Summary

---

# 🏁 Conclusion

Day 13 testing provided valuable insights into the authentication functionality and overall user experience of the HisabDo application and website.

A total of **35 test cases** were executed, including **20 mobile application test cases** and **15 website test cases**. Overall, **23 test cases passed and 12 failed**.

The major areas requiring attention are **password validation, registration validation, duplicate account prevention, password recovery, form validation, and error handling**.

Addressing these issues would improve the application's **security, reliability, usability, and overall user experience**.

---

## 👩‍💻 Intern

**Esha Tur Razia**
**Software Quality Assurance Intern**
**HisabDo SQA Internship Bootcamp**

---

## 📌 Project Status

**Testing Completed – Improvements Recommended**
