# 0x03. ES6 Data Manipulation

## Project Overview

This project focuses on mastering ES6 data manipulation techniques in JavaScript. You will learn how to use various array methods and data structures effectively.

## Learning Objectives

By the end of this project, you should be able to explain the following concepts clearly:

- Using `map`, `filter`, and `reduce` on arrays.
- Understanding typed arrays.
- Utilizing Set, Map, and WeakMap data structures.

## Resources

To assist with your learning, here are some helpful resources:

- [Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
- [Typed Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray)
- [Set Data Structure](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set)
- [Map Data Structure](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map)
- [WeakMap](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap)

## Requirements

- All your files will be executed on **Ubuntu 18.04 LTS** using **NodeJS 12.11.x**.
- Allowed editors: **vi**, **vim**, **emacs**, **Visual Studio Code**.
- All your files should end with a new line.
- A **README.md** file, at the root of the folder of the project, is mandatory.
- Your code should use the `.js` extension.
- Your code will be tested using **Jest** and the command `npm run test`.
- Your code will be verified against lint using **ESLint**.
- Your code needs to pass all tests and linting. You can verify the entire project by running `npm run full-test`.
- All of your functions must be exported.

## Setup

To set up your environment, follow these steps:

1. Install NodeJS 12.11.x (in your home directory):
   ```bash
   curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
   sudo bash nodesource_setup.sh
   sudo apt install nodejs -y
   ```
   Verify installation:
   ```bash
   $ nodejs -v
   v12.11.1
   $ npm -v
   6.11.3
   ```

2. Install Jest, Babel, and ESLint in your project directory using the supplied `package.json`:
   ```bash
   npm install
   ```

## Configuration Files

Add the following files to your project directory:

- `package.json`
- `babel.config.js`
- `.eslintrc.js`

Don’t forget to run `npm install` when you have the `package.json` file.