# JavaScript Template (2023)

This is a basic template for starting a new JavaScript project. It includes automated testing, using Jest, automated linting, using ESLint, and a continuous integration pipeline using GitHub Actions.

## To install dependencies
    npm install or npm run dev

## To test code locally (using Jest)
    npm run test

## To lint code locally (using ESLint)
    npm run lint

## To fix linting errors
    npm run lint:fix

## Automated Building and Testing: GitHub Actions
Each time that code is pushed to this repository, GitHub Actions builds the project, if applicable, and runs all tests using npm.

## License
MIT License

## Measures of Success
- [x] A programming language is selected (JavaScript)
- [x] A toolchain / runtime environment is selected (Node.js)
- [x] A testing framework is selected (Jest)
- [x] A continuous integration solution is selected (GitHub Actions)
- [x] A static analysis solution is selected (ESLint)
- [x] A code formatting solution is selected (ESLint)
- [x] A package manager solution is selected (npm)
- [x] A template git repo is created
- [x] Static analysis and code formatting are pre-configured in the repo as restrictively as possible
- [x] There is a “Hello World” program in the repo (hello.js)
- [x] There is a test in the repo that asserts that 2 + 2 == 4 (sum.test.js)
- [x] There is a CI pipeline that runs the test (GitHub Actions - node.js.yml)
- [x] A README.md file describes how to use repo
- [x] The repo should have an appropriate .gitignore
- [x] The repo should have an appropriate license (MIT License)