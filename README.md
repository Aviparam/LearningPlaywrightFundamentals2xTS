# Learning Playwright Fundamentals 2x

This repository contains a Playwright test project that demonstrates basic browser automation and assertions using the Playwright Test framework.

## Project structure

- tests/: sample Playwright test specs
- playwright.config.ts: Playwright configuration
- package.json: project dependencies and scripts

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```
2. Install Playwright browsers:
   ```bash
   npx playwright install
   ```

## Run tests

Run the test suite:

```bash
npx playwright test
```

Run tests in headed mode:

```bash
npx playwright test --headed
```

## Notes

The sample tests visit the Playwright website and verify the page title and the "Get started" link flow.
