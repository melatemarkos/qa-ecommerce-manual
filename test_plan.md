# 📋 Test Plan: Manual QA for AutomationExercise.com 

### Table of Contents
1. [📘 Introduction](#📘-introduction)
2. [🎯 Test Objectives](#🎯-test-objectives)
3. [🗺️ Scope of Testing](#🗺️-scope-of-testing)
4. [🧪 Test Types](#🧪-test-types)
5. [🚀 Testing Approach](#🚀-testing-approach)
6. [🖥️ Test Environment](#🖥️-test-environment)
7. [📊 Test Data](#📊-test-data)
8. [🛠️ Tools and Resources](#🛠️-tools-and-resources)
9. [📬 Test Deliverables](#📬-test-deliverables)
10. [🐞 Bug Reporting Process](#🐞-bug-reporting-process)

## 📘 Introduction 
This test plan outlines the approach and scope for manually testing the website AutomationExercise. The goal is to verify the core functionality, usability, and overall stability of the application from an end-user perspective. The testing process will simulate real user actions to uncover potential defects and ensure a high-quality user experience. Cross-browser testing will be included to validate consistent behavior across major browsers such as Chrome, Firefox, and Edge.

Manual test cases are based on the official test cases published by the AutomationExercise platform, adapted and executed to validate core user functionalities and workflows.

This project demonstrates comprehensive manual testing skills—including test planning, case execution, defect reporting, and documentation—and serves as a practical portfolio piece showcasing my QA expertise.

## 🎯 Test Objectives

The objective of this test effort is to ensure the quality and functionality of the AutomationExercise website by:

→ Verifying that all core user functionalities perform as expected across the defined test cases.<br>
→ Identifying and documenting any defects, inconsistencies, or usability issues.<br>
→ Ensuring a seamless end-to-end user experience for key workflows.<br>

## 🗺️ Scope of Testing

This test plan covers the manual functional end-to-end testing of the AutomationExercise website, focusing on all 26 official test cases provided on the platform. The scope includes validating core features such as:

✅ User registration and login/logout <br>
✅ Product search and product details <br>
✅ Shopping cart functionality <br>
✅ Checkout and payment process <br>
✅ Subscription management <br>
✅ Contact forms <br>
✅ Social media links <br>

Testing will ensure that each feature behaves as expected from a user’s perspective.

**Out of scope:** Non-functional aspects such as performance testing, security testing, and backend database validation, which will be considered in future testing phases or automated test efforts.

## 🧪 Test Types

This manual testing effort includes the following types of testing:

- ✅ **Functional Testing** – To validate that each feature behaves as expected.
- 🔁 **End-to-End Testing** – To ensure that key user workflows (e.g., registration to checkout) perform seamlessly.
- 🧭 **Usability Testing** – To assess the ease of navigation and clarity of UI elements.
- 🌐 **Cross-browser Testing** – To verify consistent behavior across Chrome, Firefox, and Edge.
  
## 🚀 Testing Approach

✦ The testing process will follow a **black-box manual testing methodology**, focusing on validating the system from an end-user perspective without knowledge of internal code structure <br>

✦ Functional **end-to-end test cases** will be executed against the live production environment of AutomationExercise.<br>

✦ Tests will be prioritized based on **critical user flows**, such as account registration, login, product search, and checkout.<br>

✦ **Cross-browser testing** will be performed using BrowserStack to validate functionality across multiple web browsers (Chrome, Firefox, Safari).<br>

✦ Defects or unexpected behavior will be logged and documented in a structured format including steps to reproduce, expected vs actual results, and severity.<br>

✦ Testing will be conducted using a combination of desktop and mobile browser environments to assess responsiveness.<br>

## 🖥️ Test Environment
The testing will be performed under the following environments to simulate real-world user conditions:

- **Local Environment:**<br>
  - Browser: Google Chrome (latest version)<br>
  - Operating System: Windows 10<br>
  - Device: Desktop/Laptop<br>

- **Cross-Browser Testing (via BrowserStack):**<br>
  - Browsers: Firefox, Safari, Microsoft Edge (latest versions)<br>
  - Platforms: Windows 10, macOS, iOS, Android emulators<br>
  - Devices: Desktop and mobile emulation (responsive behavior checks)<br>

BrowserStack will be used to validate cross-browser compatibility and ensure consistent functionality across various platforms and screen sizes.

## 📊 Test Data

The following test data will be used during manual testing to validate form fields, workflows, and user interactions across the site:

- **User Credentials:**
  - Valid:
    - Email: `testuser@example.com`
    - Password: `Test@1234`
  - Invalid:
    - Email: `invaliduser@example.com`
    - Password: `wrongpass`

- **Registration Data:**
  - Name: `Test User`
  - Email: `testuser+{timestamp}@example.com` *(unique for repeated tests)*
  - Title: `Mrs.`
  - Date of Birth: `01 January 1990`
  - Address: `123 QA Lane`
  - State: `Testville`
  - Country: `United States`
  - Zipcode: `12345`
  - Mobile Number: `123-456-7890`

- **Payment Details (Mock Inputs):**
  - Name on Card: `Test User`
  - Card Number: `1234 1234 1234 1234` *(Visa test number)*
  - CVC: `321`
  - Expiry: `01/30`

- **Subscription Email:**
  - Valid: `subscriber@example.com`
  - Invalid: `notanemail@example.com`

> ℹ️ *Test data will be reused across multiple test cases and adjusted where necessary to cover edge cases or negative testing.*


## 🛠️ Tools and Resources

The following tools and resources will be used throughout the manual testing process to ensure efficient execution, documentation, and defect tracking:

#### ● Browsers
- **Google Chrome** (local testing) ![Chrome](https://img.shields.io/badge/Chrome-4285F4?style=flat&logo=googlechrome&logoColor=white)
- **Mozilla Firefox**, **Safari**, **Microsoft Edge** (via BrowserStack for cross-browser testing)
  ![Firefox](https://img.shields.io/badge/Firefox-FF7139?style=flat&logo=firefox-browser&logoColor=white)![Safari](https://img.shields.io/badge/Safari-000000?style=flat&logo=safari&logoColor=white)![Edge](https://img.shields.io/badge/Edge-0078D7?style=flat&logo=microsoft-edge&logoColor=white)



#### ● Operating Systems
- **Windows 10** (local machine) ![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white)
- **macOS**, **iOS**, **Android** (via BrowserStack)![macOS](https://img.shields.io/badge/macOS-000000?style=flat&logo=apple&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat&logo=apple&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)


#### ● Devices
- **Desktop/Laptop** (primary testing device) <span style="font-size:20px;">💻</span>
- **Mobile emulation** (for responsive checks) <span style="font-size:20px;">📱</span>

#### ● Testing Tools
- **BrowserStack** – Cross-browser and responsive testing platform  ![BrowserStack](https://img.shields.io/badge/BrowserStack-ff6e00?style=flat&logo=browserstack&logoColor=white)
- **Google Sheets** – For maintaining test cases, tracking execution status, and recording results.  ![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=flat&logo=googlesheets&logoColor=white)
- **GitHub Issues** – For logging and tracking bugs found during manual testing.  ![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
- **Snipping Tool** – For capturing screenshots of bugs or failed test cases <span style="font-size:20px;">📸</span>

- **VS Code /Notepad++** – For editing Markdown files and notes ![VS Code](https://img.shields.io/badge/VSCode-007ACC?style=flat&logo=visualstudiocode&logoColor=white)

## 📬 Test Deliverables

The following artifacts will be produced and maintained throughout the manual testing process:

- **Test Cases**: Detailed documentation of all executed test cases with expected vs actual results.
- **Test Execution Reports**: Summaries of testing activities including passed, failed, and blocked test cases.
- **Defect Reports**: Logged bugs with detailed reproduction steps, severity, screenshots, and status updates.
- **Test Summary Report**: Final report summarizing the overall testing outcomes, coverage, and quality status.
- **Recommendations**: Suggestions for improvements based on testing findings, including usability and functional enhancements.

## 🐞 Bug Reporting 

- **Identify and Document:** When a defect is found, record detailed information including steps to reproduce, expected behavior, actual behavior, and screenshots if applicable.

- **Log in Tracking Tool:** Log in Tracking Tool: Enter the bug into GitHub Issues, the defect tracking system used in this project. Each issue includes detailed reproduction steps, expected vs actual behavior, severity, labels, and attachments such as screenshots or logs.

ℹ️ *Note: As this is a manual testing demonstration on a live site, verification, communication, retesting, and closure steps are outside the scope of this project.*
ℹ️ GitHub’s issue tracker is used here to simulate real-world bug reporting workflows in open-source and Agile projects.

