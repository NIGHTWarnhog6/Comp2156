## Exercise 3 – GitHub Actions CI

This repository uses **GitHub Actions** to implement a Continuous Integration (CI) pipeline.

### Workflow Details
- Workflow file: `.github/workflows/ci.yml`
- Triggered on:
  - Push to the `main` branch
  - Pull requests targeting the `main` branch
- Environment: `ubuntu-latest`
- Purpose:
  - Checkout repository code
  - Set up Node.js
  - Verify the CI pipeline runs successfully

### Status
The CI pipeline runs successfully and completes without errors.

