# Cypress ParaBank Automation

End-to-end test automation framework for the **ParaBank** application using **Cypress**.

## Application Under Test

**ParaBank:**
https://parabank.parasoft.com/parabank/

## Tech Stack

* Cypress
* JavaScript
* Node.js
* npm
* Git & GitHub
* GitHub Actions

## Project Structure

```text
cypress-parabank/
│
├── cypress/
│   ├── e2e/
│   │   ├── auth/
│   │   ├── accounts/
│   │   ├── transactions/
│   │   └── users/
│   │
│   ├── fixtures/
│   ├── pages/
│   ├── support/
│   │   ├── commands/
│   │   └── utils/
│   └── test-data/
│
├── config/
├── docs/
├── reports/
├── .github/
│   └── workflows/
│
├── cypress.config.js
├── package.json
├── package-lock.json
└── .gitignore
```

## Test Coverage

The project will cover functional and end-to-end scenarios including:

* User registration
* Login and logout
* Account management
* Account creation
* Balance verification
* Fund transfers
* Bill payment
* Transactions
* Negative and validation scenarios

## Getting Started

### Prerequisites

* Node.js
* npm
* Git

### Installation

Clone the repository and install dependencies:

```bash
npm install
```

### Open Cypress

```bash
npx cypress open
```

### Run Tests

Run tests in headless mode:

```bash
npx cypress run
```

## Development Workflow

We follow a team-based development workflow:

```text
Jira Story
    ↓
Create Feature Branch
    ↓
Develop Test
    ↓
Run Tests
    ↓
Commit Changes
    ↓
Create Pull Request
    ↓
Code Review
    ↓
Merge
```

## Branch Naming

Use descriptive branch names:

```text
feature/<jira-id>-<short-description>
bugfix/<jira-id>-<short-description>
```

Example:

```text
feature/PAR-101-login-validation
```

## Pull Requests

Every change should be submitted through a Pull Request.

PRs should include:

* Jira ticket reference
* Description of changes
* Test scenarios covered
* Test execution result
* Any known limitations

## Contribution

All team members are expected to:

1. Pick or receive a Jira ticket.
2. Create a feature branch.
3. Implement the required automation.
4. Execute the relevant tests.
5. Raise a Pull Request.
6. Review other team members' Pull Requests.
7. Address review comments.
8. Merge only after approval.

## Project Goal

This project is designed to provide practical experience with:

* Cypress automation
* JavaScript
* Page Object Model
* Test data management
* API testing
* Assertions and validations
* Git branching and Pull Requests
* Code reviews
* Jira-based task management
* CI/CD with GitHub Actions
* Test reporting
* Real-world team collaboration
