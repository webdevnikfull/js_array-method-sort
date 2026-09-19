# 🧪 QA Portfolio: Array Sorting Algorithm Validation

> **About this repository:** This project focuses on the foundation of the Agile Testing Pyramid: **Unit Testing**. It demonstrates how to validate core JavaScript algorithms and array manipulation methods using automated unit tests, static analysis, and continuous integration.

![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Unit Testing](https://img.shields.io/badge/-Unit_Testing-C21325?style=for-the-badge&logo=jest&logoColor=white)
![ESLint](https://img.shields.io/badge/-Static_Analysis-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-CI/CD-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

## 🎯 Project Overview

This repository contains a custom JavaScript implementation for sorting arrays (`src/arrayMethodSort.js`). 

As a **QA Automation Engineer**, my goal here is to ensure the algorithmic logic is flawless by writing and maintaining comprehensive unit tests (`src/arrayMethodSort.test.js`) that cover standard use cases, boundary values, and potential edge cases directly at the code level.

## 🛠️ QA Tech Stack & Tools

* **Testing Level:** Unit Testing (White-Box Testing)
* **CI/CD Pipeline:** GitHub Actions (Automated testing on every push/PR)
* **Static Code Analysis (Shift-Left QA):** ESLint
* **Core Language:** JavaScript (ES6+)

## 📊 Test Strategy & Coverage

The testing strategy is designed to isolate and tightly validate the sorting function:

### 1. Unit Testing (Code Level Validation)
Located in `src/arrayMethodSort.test.js`, the automated test suite verifies:
* Correct sorting behavior for arrays containing numerical values (ascending/descending logic).
* Correct sorting behavior for string values (alphabetical order).
* Robust handling of edge cases (e.g., empty arrays, single-element arrays, undefined values).
* Mutation prevention (ensuring predictable behavior of the array elements).

### 2. Continuous Integration (CI/CD)
The project is seamlessly integrated with GitHub Actions (`.github/workflows/test.yml`). Every commit automatically triggers a pipeline that:
* Runs `ESLint` to catch syntax, logic, and style errors early.
* Executes the full unit test suite to prevent regressions from being merged into the main branch.

## 🚀 How to Run the Tests Locally

To evaluate the unit tests and static analysis tools on your local machine, follow these steps:

### 1. Environment Setup
Clone the repository and install the required Node.js dependencies:
```bash
npm install
