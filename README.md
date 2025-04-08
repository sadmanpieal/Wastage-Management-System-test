# 🐞 Bug Report - Wastage Store System

This repository provides a detailed QA bug report for the **Wastage Store System**, which handles the dispatch and management of material waste in a production environment. This report documents issues found during manual QA testing for improved system accuracy and operational performance.

---

## 📋 Project Overview

The **Wastage Store System** is designed to manage inter-departmental waste dispatch, barcode validation, and stock reconciliation. During testing, several UI, logic, and data handling issues were identified and are compiled here for review and resolution.

---

## ✅ Test Summary

| Category              | Count   |
|-----------------------|---------|
| Total Bugs Reported   | 17      |
| Critical Bugs         | 10      |
| Minor Bugs            | 7       |
| Affected Modules      | 6       |
| Current Status        | All marked as "To Do" |
| Test Coverage         | ~88%    |

---

## 📁 File Details

- **File Name**: `Bug report of Wastage Store System.xlsx`
- **Exported From**: Jira
- **Project Code**: WSS
- **Included Fields**:
  - Issue Key
  - Summary
  - Status
  - Created Date
  - Project Name & Type
  - Severity (inferred from context)
  - Comments & Reporter (if applicable)

---

## 🔍 Sample Bug Entry

| Field               | Example Value                                                                 |
|--------------------|--------------------------------------------------------------------------------|
| **Bug ID**         | WSS-17                                                                         |
| **Summary**        | Allocated QTY field is disabled in dispatch according to selected company ID   |
| **Severity**       | Critical                                                                       |
| **Status**         | To Do                                                                          |
| **Steps to Reproduce** | 1. Go to dispatch page <br>2. Select company ID <br>3. Check if Allocated QTY is editable |
| **Expected Result**| Allocated QTY field should be active based on selection                        |
| **Actual Result**  | Field remains disabled and blocks dispatch flow                                |
| **Reported Date**  | March 2, 2025                                                                  |

---

## 🔧 Modules Tested

- Dispatch Between Departments
- Barcode Field Validations
- Quantity & Allocation Inputs
- Company-based Conditional Logic
- Section & Machine ID Tracking
- UI Dropdown Interaction

---

## 🎯 Purpose

This QA report was compiled to:

- Log and categorize issues affecting system usability and data flow
- Ensure accuracy in dispatch procedures across multiple companies
- Aid developers in reproducing and resolving reported bugs
- Serve as a central reference for tracking future bug resolutions

---

## 🙋‍♂️ Author

**Name**: Md. Sadman Shahrieal Pieal  
**Role**: QA Engineer  
**Email**: sadmanpieal@gmail.com  
**Date**: March 2025

---

## 🧭 Future Enhancements

- Enable dynamic form behavior for company-based fields
- Add client-side validations for negative quantity input
- Integrate form testing into CI/CD pipeline
- Improve tracking of dispatched vs returned items in logs

---

## 📌 Disclaimer

This report is intended solely for internal QA and development purposes. All issue data reflects the status as of March 2025 and is subject to revision based on future sprints or product changes.
