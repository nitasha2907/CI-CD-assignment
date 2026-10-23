# CI/CD Automated Pipeline Assignment

## Application Description
This is a lightweight web application created for demonstrating a complete Continuous Integration and Continuous Deployment (CI/CD) pipeline using GitHub Actions.

## Directory Structure
- `.github/workflows/`: Contains GitHub Actions workflow definitions (`ci.yml` and `deploy.yml`).
- `src/`: Application source code (`index.html`).
- `tests/`: Automated test suite (`test.js`).
- `README.md`: Project documentation.

## How to Run Tests
The repository uses a Node.js validation script located in `tests/test.js`. To execute the test locally, run:
```bash
node tests/test.js
