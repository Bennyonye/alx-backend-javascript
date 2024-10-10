# 0x04. TypeScript

## Description

This project focuses on TypeScript, a superset of JavaScript that introduces static typing and other powerful features to write cleaner, error-free, and scalable code. By the end of this project, you will understand the basic and advanced concepts of TypeScript and how to integrate it into your JavaScript projects.

## Learning Objectives

By completing this project, you should be able to:

- Understand and use basic types in TypeScript.
- Define and implement interfaces, classes, and functions.
- Work with the DOM using TypeScript.
- Utilize generic types for reusable and type-safe code.
- Create and manage namespaces.
- Merge declarations to extend types or interfaces.
- Use ambient namespaces to import external libraries.
- Implement basic nominal typing with TypeScript.

## Resources

To complete this project, refer to the following resources:

- [TypeScript in 5 minutes](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)

## Project Requirements

- **Allowed editors**: `vi`, `vim`, `emacs`, `Visual Studio Code`
- All your files should end with a new line.
- All your files will be transpiled on **Ubuntu 18.04**.
- Your TypeScript scripts will be checked with Jest (`version 24.9.*`).
- A `README.md` file, at the root of the project folder, is mandatory.
- Your code should use the `.ts` extension when possible.
- The TypeScript compiler should not show any warnings or errors when compiling your code.

## Configuration Files

### `package.json`
The `package.json` file manages the project dependencies and provides scripts for building and testing your TypeScript code. Make sure you have a `package.json` with the appropriate configurations and dependencies before starting.

### `.eslintrc.js`
This file configures the ESLint rules for the project. It ensures that your code follows consistent formatting and quality standards.

### `tsconfig.json`
The `tsconfig.json` file contains the settings for the TypeScript compiler, including options such as module resolution, type checking, and target JavaScript version.

### `webpack.config.js`
This file configures Webpack to bundle and transpile TypeScript files. Webpack will help optimize your code and handle file dependencies efficiently.

## Setup Instructions

### Step 1: Install TypeScript and Other Dependencies
1. Make sure Node.js and npm are installed on your system.
2. Navigate to the project directory and install the necessary dependencies by running:
   ```bash
   npm install
   ```

### Step 2: Compile TypeScript Files
To compile your TypeScript files, run the TypeScript compiler:
```bash
tsc
```

### Step 3: Lint the Code
Check for linting errors using ESLint:
```bash
npm run lint
```

### Step 4: Run Tests
To run tests with Jest, use the following command:
```bash
npm run test
```

## Project Structure

The typical project structure for this TypeScript project is as follows:

```
├── dist/                # Compiled JavaScript files
├── src/                 # TypeScript source files
│   ├── index.ts         # Main entry point
│   └── *.ts             # Additional TypeScript files
├── package.json         # Project configuration and dependencies
├── tsconfig.json        # TypeScript compiler configuration
├── .eslintrc.js         # ESLint configuration
├── webpack.config.js    # Webpack configuration
└── README.md            # Project description and setup instructions
```

## Tasks Overview

### 0. Basic Types
- **Task**: Create TypeScript files that demonstrate how to use basic types like `string`, `number`, `boolean`, `array`, `tuple`, `enum`, and `any`.
- **Output**: A script that utilizes these types and outputs their values.

### 1. Interfaces and Classes
- **Task**: Define and implement interfaces and classes. Show how to create and manipulate objects using these constructs.
- **Output**: TypeScript files showcasing the use of interfaces and classes.

### 2. DOM Manipulation
- **Task**: Write TypeScript code that interacts with the DOM. Include adding and removing elements, updating styles, and handling events using TypeScript.
- **Output**: A TypeScript file that demonstrates DOM manipulation techniques.

### 3. Generic Types
- **Task**: Implement generic types in functions, interfaces, and classes. Demonstrate the reusability and type safety of generic components.
- **Output**: TypeScript files using generic types in various scenarios.

### 4. Namespaces and Modules
- **Task**: Organize code using namespaces and modules to ensure better structure and maintainability.
- **Output**: TypeScript files that show the use of namespaces and modules.

### 5. Ambient Declarations and External Libraries
- **Task**: Use external libraries like `jQuery` or `lodash` with TypeScript through ambient declarations.
- **Output**: TypeScript files demonstrating the integration of external libraries.

### 6. TypeScript Configuration and Linting
- **Task**: Ensure that all TypeScript files are free from compilation errors and warnings. Configure ESLint to enforce coding standards and fix any linting issues.
- **Output**: A project free of compilation and linting errors.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd 0x04-Typescript
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Compile TypeScript files:
   ```bash
   npm run build
   ```
5. Run the development server or start the application:
   ```bash
   npm run dev
   ```

## Author
This project is developed and maintained by **BennyOnye**.