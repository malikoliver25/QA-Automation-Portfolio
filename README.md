# Enterprise QA Automation Monorepo | Java • Playwright • Appium • API

A comprehensive, enterprise-level Quality Assurance automation portfolio demonstrating cross-platform testing capabilities. This monorepo houses scalable, maintainable, and highly efficient test frameworks designed to validate UI, Mobile, API, and Database layers.

---

## Architectural Excellence

* **Design Patterns:** Implementation of **Singleton** for session management and **Factory Pattern** for cross-framework (Selenium/Playwright/Appium) instantiation.
* **Mobile Excellence:** **Appium-based** test suites for Android and iOS, validated across 5+ device configurations using **BrowserStack**.
* **Database Integrity:** Integrated **PostgreSQL** utilities for backend state verification using JOINs and subqueries to ensure UI/Mobile actions reflect correctly in the DB.
* **Data-Driven Testing:** Parameterized test suites using **TestNG Data Providers** with external **JSON and CSV** sources.
* **Performance Testing:** Load and stress testing simulation for 500+ concurrent users using **JMeter**.

---

## Live Execution & Artifacts

To maintain repository speed and health, heavy video files and execution artifacts are hosted externally.

* **[Watch Execution Demo & View Artifacts](https://drive.google.com/drive/folders/1zVxzCtdOgtxPKO9ZpSNvtv40k_vcwzf5?usp=sharing)** *(Hosted securely on Google Drive)*
* **View Live Allure Report** *(Link generated via GitHub Actions)*
* **Launch in GitHub Codespaces** *(Run tests instantly in your browser)*

---

## Project Structure

| Module | Purpose | Tech | Status |
| :--- | :--- | :--- | :--- |
| `ui-automation-selenium` | Web Testing | Java, Selenium | **Active** |
| `ui-automation-playwright` | Modern Web Testing | Java, Playwright | **In Development** |
| `mobile-automation-appium` | Mobile (iOS/Android) | Appium, Java | **In Development** |
| `api-automation-restassured` | Backend Validation | REST Assured | **In Development** |
| `db-validation-sql` | Data Integrity | PostgreSQL | **In Development** |
| `performance-jmeter` | Load Testing | JMeter | **Planned** |

---

## How To Run

**1. Clone & Navigate:**
```bash
git clone https://github.com/malikoliver25/QA-Automation-Portfolio.git
cd QA-Automation-Portfolio

Execute Full Regression:
Bash
mvn clean install

Generate Local Reports:
Bash
allure serve allure-results

Contact
LinkedIn: www.linkedin.com/in/malik-o-1b4359115
