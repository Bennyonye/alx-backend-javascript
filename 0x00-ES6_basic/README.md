# 0x00. ES6 Basics

## Description
This repository contains the project "0x00. ES6 Basics," which explores essential concepts of ECMAScript 6 (ES6). The project covers new features introduced in ES6, such as arrow functions, block-scoped variables, iterables, and iterators, among others. By the end of this project, you will be able to explain the key differences between ES6 and earlier versions of JavaScript, demonstrate an understanding of ES6 features, and implement them effectively in code.

## Learning Objectives
At the end of this project, you should be able to:

1. Explain what ES6 is.
2. Describe new features introduced in ES6.
3. Differentiate between constants and variables.
4. Use block-scoped variables (`let` and `const`).
5. Write arrow functions and use function default parameters.
6. Apply rest and spread function parameters.
7. Utilize string templating in ES6.
8. Create objects and understand their properties in ES6.
9. Implement iterators and `for-of` loops.

## Project Setup

### 1. Prerequisites
- All files are executed on **Ubuntu 18.04 LTS** using **NodeJS 12.11.x**.
- Ensure you have an appropriate code editor, such as `vi`, `vim`, `emacs`, or Visual Studio Code.
- Your code will be tested using the **Jest Testing Framework**.
- Your code will be analyzed using the linter **ESLint** with specific rules provided.

### 2. Installing NodeJS 12.11.x
Run the following commands in your home directory:

```bash
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
```

Verify the installation:

```bash
nodejs -v
# v12.11.1
npm -v
# 6.11.3
```

### 3. Install Jest, Babel, and ESLint
In your project directory, install Jest, Babel, and ESLint using the provided `package.json`:

```bash
npm install
```

### 4. Configuration Files
Add the following configuration files to your project directory:

1. **`package.json`**
2. **`babel.config.js`**
3. **`.eslintrc.js`**

### 5. Running the Project
After adding the configuration files and installing dependencies, you can run the project and execute tests using:

```bash
npm test
```

## Repository Structure
```
0x00-ES6-basics/
├── README.md           # Project documentation
├── package.json        # Project dependencies and scripts
├── babel.config.js     # Babel configuration file for ES6+ support
├── .eslintrc.js        # ESLint configuration file
├── *.js                # ES6 source code files
└── __tests__/          # Jest test cases for the project
```

## Author
**BennyOnye**