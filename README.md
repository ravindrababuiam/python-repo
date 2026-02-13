# Simple Express API

A basic Express.js REST API with GitHub Actions CI/CD setup.

## Features

- RESTful API endpoints
- User management
- Health check endpoint
- Automated testing with Jest
- CI/CD with GitHub Actions

## API Endpoints

- `GET /` - Welcome message
- `GET /api/health` - Health check
- `GET /api/users` - Get all users
- `GET /api/users/:id` - Get user by ID
- `POST /api/users` - Create new user

## Setup

1. Install dependencies:
```bash
npm install
```

2. Run the server:
```bash
npm start
```

3. Run in development mode:
```bash
npm run dev
```

4. Run tests:
```bash
npm test
```

## Testing

The application includes comprehensive tests using Jest and Supertest.

Run tests with coverage:
```bash
npm test
```

## GitHub Actions CI/CD

This project includes a GitHub Actions workflow that:
- Runs on push to `dev` branch
- Installs dependencies
- Runs linting (if configured)
- Runs all tests
- Generates test coverage report

See `.github/workflows/ci.yml` for the full workflow configuration.
