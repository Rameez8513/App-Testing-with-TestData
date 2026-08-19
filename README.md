# Mobile-App-Testing
Automated mobile QA test suite for an app-downloader Android application, built with Katalon Studio and UiAutomator2.
# AppStore QA Automation

Automated mobile testing suite for a third-party Android app-downloader application, built using **Katalon Studio** with **UiAutomator2**. This project demonstrates end-to-end mobile test automation — from test case design through execution and reporting — following standard STLC (Software Testing Life Cycle) principles.

## Overview

This suite covers core user-facing flows of the application under test, validating navigation, search functionality, and UI element behavior on a real Android device.

## Tools & Technologies

- **Katalon Studio** — test automation IDE
- **Appium (UiAutomator2)** — underlying mobile automation engine
- **Android SDK / ADB** — device communication
- **Git** — version control

## Test Cases

| ID | Name | Description | Priority |
|----|------|-------------|----------|
| TC_Search_001 | Verify Search button navigation | Confirms tapping the Search icon in the bottom navigation bar correctly routes to the Search screen | High |
| *(add more as you build them)* | | | |

## Project Structure

```
├── Test Cases/          # Individual automated test scripts
├── Object Repository/   # Captured UI element locators
├── Test Suites/         # Grouped test case collections
├── Reports/             # Execution results (pass/fail, screenshots)
└── Profiles/            # Environment configurations
```

## How to Run

1. Open project in Katalon Studio
2. Connect an Android device via USB with debugging enabled
3. Open desired Test Suite under `Test Suites/`
4. Click **Run** and select target device
5. View results under `Reports/`

## Author

Rameez — Final-year CS student, Flutter/Mobile App Developer, exploring SQA & mobile test automation.
