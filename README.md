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

  - Operating systems (desktop/mobile)
  - Browser requirements
  - Assistive technologies
   - NVDA, Jaws, Voiceover, Narrator, Talkback

- **Training and Awareness**
  - Onboarding new members
    - Accessibility training (Crash-course)
    - Glossary, Cheatsheets, checklists
  - Rituals
    - WCAG Guidelines Review
  - Schedule accessibility training for the team.
  - Share resources on accessibility best practices.

## Design
- **Training**
  - Universal Design 
  - Inclusive Design
  - WCAG Guidelines for UX designers
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
  - CSS
  - Javascript
  - Ensure all interactive elements are focusable and operable.
  - More to come
  - boilerplates

  Links:
  - https://developer.mozilla.org/en-US/docs/Learn/Accessibility/CSS_and_JavaScript


- **Use of ARIA Best/Bad Practices**
  - Implement ARIA roles and properties where necessary.
  - More to come

- **Design Tokens**

- 

 
### Accessibility Linting Tools

- **ESLint with Accessibility Plugins** – ESLint-plugin-jsx-a11y: This is a static AST checker for accessibility rules on JSX elements.

- **Stylelint-a11y** – A plugin that enforces CSS rules that are important for accessibility, such as color contrast and text size.

- AXE-core 
- Needs more research

## Testing
- **Automated Testing** – Integrate accessibility testing tools (e.g., Axe, Pa11y, Lighthouse) into the CI/CD pipeline.
  - More to come.
  - Unit Testing
  - test-drive development (TDD)
  - Test runners
    - Cypress
    - Pupperteer

  - Review this list: 
    - [https://a11y-automation.dev/automated-tools](https://a11y-automation.dev/automated-tools) 

- **Manual Testing**
  – Conduct screen reader tests with actual users.
  - Perform keyboard-only navigation testing.
  - Tools to help conducting manual tests
    - TPGI ARC, Deque's AXE (single page - free) 
    - Review this list: [https://github.com/topics/accessibility-checker](https://github.com/topics/accessibility-checker)
    - More to come.

## Deployment
- **Accessibility Statement** – Publish an up-to-date accessibility statement on the website.

- **User Feedback** – Provide a mechanism for users to report accessibility issues.

## Maintenance
- **Regular Audits** – Monitor/schedule regular accessibility audits to ensure ongoing compliance.

- **Update Training** – Keep the development team updated on the latest accessibility standards and tools.

---

--- Work in Progress ---
