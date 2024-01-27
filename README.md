# Architecture reference for Node.js applications

## Installation

```sh
# Install dependencies.
npm install
```

## Scripts

```sh
# Development script to run the application using nodemon and register tsconfig-paths.
npm run dev

# Start script to run the built application using node.
npm run start

#Test script to run unit tests with coverage.
npm run test

# Unit test script to run Jest with verbose output for the ./test/unit/ directory.
npm run test:unit

# Coverage test script to run Jest with verbose output for the ./test/unit/ directory and generate coverage report.
npm run test:coverage

# Build script to compile TypeScript files using tsc.
npm run build

#Lint script to run ESLint and fix linting issues.
npm run lint

# Prepare script to install Husky hooks.
npm run prepare

# Reset script to remove all dependencies and lock files.
npm run reset

# Clear build script to remove all build files.
npm run clear:build

# Clear coverage script to remove all coverage files.
npm run clear:coverage
```
