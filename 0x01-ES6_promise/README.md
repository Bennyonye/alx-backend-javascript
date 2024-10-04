# 0x02. ES6 Classes

## Description
This project explores the concept of classes in JavaScript, a key feature introduced in ES6 (ECMAScript 2015). It delves into object-oriented programming (OOP) principles, providing practical examples and exercises to help you understand how to define classes, add methods, and extend them. You will also learn about metaprogramming and the use of symbols.

## Learning Objectives
By the end of this project, you should be able to explain and implement the following concepts without external references:

- How to define a class in JavaScript
- Adding methods to a class
- Creating static methods for a class
- Extending a class from another class
- Understanding metaprogramming and symbols in JavaScript

## Project Requirements
The following conditions must be met to run the project:

- All files will be executed on **Ubuntu 18.04 LTS** using **NodeJS 12.11.x**
- Preferred editors: `vi`, `vim`, `emacs`, `Visual Studio Code`
- All files should end with a new line
- Use the `.js` extension for all JavaScript files
- Testing will be done using **Jest** and the command `npm run test`
- Linting will be done using **ESLint**
- Your code should pass all tests and lint checks; run `npm run full-test` to verify

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
nodejs -v  # Should output v12.11.1 or similar
npm -v     # Should output 6.11.3 or similar
```

### 2. Install Dependencies
In your project directory, ensure you have the following dependencies:

- **Jest**: For testing JavaScript code.
- **Babel**: For JavaScript transpilation.
- **ESLint**: For code linting and style guide enforcement.

If these dependencies are specified in your `package.json` file, run:

```bash
npm install
```

### 3. Configuration Files
Ensure that the following configuration files are present in your project directory:

- **`package.json`**: Contains project dependencies and scripts.
- **`babel.config.js`**: Configuration for Babel.
- **`.eslintrc.js`**: Configuration for ESLint.

### 4. Run Tests and Lint
You can run the tests and lint your code using the commands below:

- **Run Jest Tests**:

  ```bash
  npm run test
  ```

- **Run Full Test and Lint**:

  ```bash
  npm run full-test
  ```

## How to Use This Repository
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/YourUsername/0x02-ES6-classes.git
   ```

2. Navigate to the project directory:
   ```bash
   cd 0x02-ES6-classes
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Start working on the project by creating and modifying `.js` files as specified in the project tasks.

5. Run the tests and lint checks regularly to ensure code quality and functionality.

## Additional Resources
For more information on the concepts covered in this project, refer to the following resources:

- [Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
- [Metaprogramming](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Meta_programming)

## Author
This project is developed and maintained by **BennyOnye**.
