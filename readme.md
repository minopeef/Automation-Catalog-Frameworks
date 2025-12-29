# Automation Frameworks Catalog

A comprehensive catalog of test automation frameworks across different platforms and languages.

## Overview

This catalog tracks automation framework implementations, their status, and repository information. Each framework follows the guidelines defined in `automation_framework_guidelines.md` to ensure consistency, modularity, and maintainability.

## Framework Status

| Platform | Framework | Suggested Repo Name | Status | Repository | Contributor |
|----------|-----------|---------------------|--------|------------|-------------|
| Java | Playwright Java BDD | playwright-java-bdd-sample | Completed | Test-Architect/playwright-java-bdd-sample | lamhotsiagian |
| Java | Selenium WebDriver | selenium-java-sample | Pending | - | - |
| Java | TestNG | testng-java-sample | Pending | - | - |
| Java | JUnit 5 | junit5-java-sample | Pending | - | - |
| Java | Cucumber-JVM | cucumber-java-bdd-sample | Pending | - | - |
| Java | Rest Assured | rest-assured-java-sample | Completed | Test-Architect/rest-assured-java-sample | thananauto |
| Python | PyTest | pytest-python-sample | Completed | Test-Architect/pytest-python-sample | IsraelW18 |
| Python | Robot Framework | robotframework-python-sample | Completed | Test-Architect/robotframework-python-sample | emasmirza03 |
| Python | Behave | behave-python-bdd-sample | Pending | - | - |
| Python | Lettuce | lettuce-python-sample | Pending | - | - |
| Python | unittest | unittest-python-sample | Pending | - | - |
| TypeScript | Playwright | playwright-typescript-sample | Completed | - | - |
| TypeScript | Cypress | cypress-typescript-sample | Completed | srthorat/sauce-lab-ats-cypress-typescript | srthorat |
| TypeScript | Jest | jest-typescript-sample | Completed | srthorat/petstore-ts | srthorat |
| TypeScript | Mocha + Chai | mocha-chai-ts-sample | Pending | - | - |
| TypeScript | Cucumber.js (TS) | webdriverio-ts-bdd-sample | Completed | Test-Architect/webdriverio-js-sample | kennyfrans |
| JavaScript | Playwright | playwright-js-sample | Completed | Test-Architect/playwright-typescript-sample | thananauto |
| JavaScript | Cypress | cypress-js-sample | Pending | - | - |
| JavaScript | Jest | jest-js-sample | Pending | - | - |
| JavaScript | Mocha + Chai | mocha-chai-js-sample | Pending | - | - |
| JavaScript | WebdriverIO | webdriverio-js-sample | Pending | - | - |
| JavaScript | TestCafe | testcafe-js-sample | Pending | - | - |
| JavaScript | Cucumber.js | cucumber-js-sample | Pending | - | - |
| Appium | Appium Java Client | appium-java-sample | Pending | - | - |
| Appium | Appium Python Client | appium-python-sample | Pending | - | - |
| Appium | Appium JavaScript Client | appium-js-sample | Pending | - | - |
| Appium | WebdriverIO + Appium Plugin | webdriverio-appium-sample | Pending | - | - |
| Appium | Appium TypeScript Client | appium-typescript-sample | Pending | - | - |

## Status Legend

- **Completed**: Framework implementation is complete and available
- **Pending**: Framework implementation is planned but not yet started

## Guidelines

All frameworks in this catalog should follow the guidelines defined in `automation_framework_guidelines.md`. These guidelines ensure that each framework is:

- Modular and maintainable
- Configuration-driven
- Data-driven and parameterized
- Reusable and extensible
- Well-documented
- CI/CD ready

## Contributing

When contributing a new framework implementation:

1. Follow the naming convention: `{framework}-{language}-sample`
2. Ensure the implementation follows all guidelines in `automation_framework_guidelines.md`
3. Include at least one executable sample test
4. Provide comprehensive documentation
5. Update this catalog with the repository link and your GitHub username
