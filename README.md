# Accessibility Best Practices for Teams (Outline)
Accessibility checkpoints and best practices for product development lifecycle.

Authors: Daniel May, Marcelo Paiva, and John Toles

## Introduction
This document outlines the key accessibility checkpoints to be integrated into the product development lifecycle. Ensuring accessibility at each stage not only enhances usability but also complies with legal standards like the ADA and WCAG.

## Table of Contents
- [Planning](#planning)
- [Design](#design)
- [Development](#development)
- [Testing](#testing)
- [Deployment](#deployment)
- [Maintenance](#maintenance)

## Planning
- **Define Accessibility Goals and Requirements**
  - Identify target accessibility standards (e.g., WCAG 2.1 AA).
  - Consider user personas that include people with disabilities.

- **Training and Awareness**
  - Schedule accessibility training for the team.
  - Share resources on accessibility best practices.

## Design
- **Accessible Design Principles**
  - Use sufficient contrast ratios.
  - Design for keyboard-only and screen reader users.
  - More to come

- **Design Review**
  - Conduct accessibility reviews of wireframes and mockups.
  - Utilize tools like color contrast analyzers and design checklists.
  - More to come

## Development
- **Coding Standards**
  - Follow semantic HTML practices.
  - Ensure all interactive elements are focusable and operable.
  - More to come

- **Use of ARIA**
  - Implement ARIA roles and properties where necessary.
  - More to come
 
### Accessibility Linting Tools

- **ESLint with Accessibility Plugins** – ESLint-plugin-jsx-a11y: This is a static AST checker for accessibility rules on JSX elements.

- **Stylelint-a11y** – A plugin that enforces CSS rules that are important for accessibility, such as color contrast and text size.

## Testing
- **Automated Testing** – Integrate accessibility testing tools (e.g., Axe, Pa11y, Lighthouse) into the CI/CD pipeline.
  - More to come.
  - Review this list: [https://a11y-automation.dev/automated-tools](https://a11y-automation.dev/automated-tools) 

- **Manual Testing**
  – Conduct screen reader tests with actual users.
  - Perform keyboard-only navigation testing.
  - Tools to help conducting manual tests
    - More to come.
    - Review this list: [https://github.com/topics/accessibility-checker](https://github.com/topics/accessibility-checker)

## Deployment
- **Accessibility Statement** – Publish an up-to-date accessibility statement on the website.

- **User Feedback** – Provide a mechanism for users to report accessibility issues.

## Maintenance
- **Regular Audits** – Schedule regular accessibility audits to ensure ongoing compliance.

- **Update Training** – Keep the development team updated on the latest accessibility standards and tools.

---

--- Work in Progress ---
