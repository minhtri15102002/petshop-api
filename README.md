# Petshop API

## API Testing

This project uses **Postman** and **Newman** for API testing.

### Local Testing

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run tests:
   ```bash
   npm run test:api
   ```

The report will be generated in `reports/report.html`.

### CI/CD Integration

Tests are automatically run on every push and pull request to `main` and `develop` branches using GitHub Actions. You can find the workflow in `.github/workflows/postman-tests.yml`.