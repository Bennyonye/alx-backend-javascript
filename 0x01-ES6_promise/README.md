# 0x01. ES6 Promises

## Description
This project focuses on using **Promises** in JavaScript, which are a key feature introduced in ES6 (ECMAScript 2015) for handling asynchronous operations. You will learn how to create, manage, and use promises effectively in your JavaScript applications, including using the `then`, `catch`, and `resolve` methods. Additionally, you will gain familiarity with `async` functions, the `await` operator, and handling errors with `throw` and `try-catch` blocks.

## Learning Objectives
By the end of this project, you should be able to explain and demonstrate the following concepts:

- What Promises are, how they work, and why they are used.
- How to use the `then`, `resolve`, and `catch` methods with Promises.
- How to use each method of the Promise object.
- How to use the `await` operator and `async` functions.
- How to handle errors using `throw` and `try-catch` blocks.

## Project Requirements
To complete and run the project, the following requirements must be met:

- All files will be executed on **Ubuntu 18.04 LTS** using **NodeJS 12.11.x**.
- Allowed editors: `vi`, `vim`, `emacs`, `Visual Studio Code`.
- All files should end with a new line.
- A `README.md` file is mandatory at the root of the project folder.
- Use the `.js` extension for all JavaScript files.
- Your code will be tested using **Jest** with the command `npm run test`.
- Your code will be verified against lint rules using **ESLint**.
- All functions must be exported.

## Project Setup
### 1. Install NodeJS 12.11.x
In your home directory, run the following commands to install NodeJS:

```bash
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
```

Verify the installation:

```bash
nodejs -v   # Should output v12.11.1 or a similar version
npm -v      # Should output 6.11.3 or a similar version
```

### 2. Install Project Dependencies
In your project directory, make sure you have the necessary dependencies specified in your `package.json` file. Run:

```bash
npm install
```

This will install **Jest**, **Babel**, and **ESLint** for testing, transpilation, and code linting, respectively.

### 3. Configuration Files
Ensure that the following configuration files are present in your project directory:

- **`package.json`**: Contains project dependencies and scripts.
- **`babel.config.js`**: Configuration file for Babel.
- **`.eslintrc.js`**: Configuration file for ESLint.
- **`utils.js`**: Contains utility functions like `uploadPhoto` and `createUser` to be used in specific tasks.

### 4. Run Tests and Lint
Use the following commands to run tests and check for code quality:

- **Run Jest Tests**:

  ```bash
  npm run test
  ```

- **Run Lint Checks**:

  ```bash
  npm run lint
  ```

- **Run Full Test**: This command will run both tests and lint checks.

  ```bash
  npm run full-test
  ```

## How to Use This Repository
1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/YourUsername/0x01-ES6-promises.git
   ```

2. Navigate to the project directory:

   ```bash
   cd 0x01-ES6-promises
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

4. Start implementing the tasks and creating `.js` files as required.

5. Run the provided Jest tests to ensure your code works as expected.

6. Lint your code regularly to ensure it adheres to the coding standards.

## Response Data Format
The following response formats will be used by some utility functions within the project:

- **`uploadPhoto`**: Returns a response with the following format:

  ```json
  {
    "status": 200,
    "body": "photo-profile-1"
  }
  ```

- **`createUser`**: Returns a response with the following format:

  ```json
  {
    "firstName": "Guillaume",
    "lastName": "Salva"
  }
  ```

## Additional Resources
For more information on Promises and asynchronous programming in JavaScript, refer to the following resources:

- [Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
- [JavaScript Promise: An introduction](https://developers.google.com/web/fundamentals/primers/promises)
- [Await and Async](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function)
- [Try and Throw](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/try...catch)

## Author
This project is developed and maintained by **BennyOnye**.
