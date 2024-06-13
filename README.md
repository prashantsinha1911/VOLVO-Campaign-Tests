
# Volvo Campaign Tests

## Setup

1. Clone the repository
2. Run `npm install` to install dependencies

## Running Tests

### Locally

To run tests locally, use:

```bash
npx wdio run wdio.conf.js
```

### With Docker

To run tests with Docker, use:

```bash
docker-compose up --build
```

## Reporting

Allure reports can be generated with:

```bash
allure generate allure-results --clean
allure open
```
