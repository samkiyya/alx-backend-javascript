# 0x00. ES6 Basics

## Description

This project focuses on the basics of ECMAScript 6 (ES6), which introduces new features and improvements to the JavaScript programming language. The aim is to explore and implement these features through practical coding exercises.

## Project Details

- **Language**: JavaScript
- **Weight**: 1
- **Start Date**: September 29, 2024, 8:00 PM
- **End Date**: September 30, 2024, 8:00 PM
- **Checker Release**: September 30, 2024, 2:00 AM
- **Auto Review**: Launched at the deadline

## Concepts

For this project, you are expected to review and understand the following concepts:

- JavaScript programming
- Software Linter

## Resources

Read or watch the following materials:

- [ECMAScript 6 - ECMAScript 2015](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Introduction)
- [Statements and declarations](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements)
- [Arrow functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
- [Default parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/default_parameters)
- [Rest parameter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters)
- [JavaScript ES6 — Iterables and Iterators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Iteration)

## Learning Objectives

By the end of this project, you should be able to explain to anyone, without the help of Google:

- What ES6 is
- New features introduced in ES6
- The difference between a constant and a variable
- Block-scoped variables
- Arrow functions and function parameters that default to them
- Rest and spread function parameters
- String templating in ES6
- Object creation and their properties in ES6
- Iterators and for-of loops

## Requirements

### General

- All files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All files should end with a new line
- A `README.md` file, at the root of the folder of the project, is mandatory
- Code should use the `.js` extension
- Code will be tested using the Jest Testing Framework
- Code will be analyzed using the linter ESLint with specific rules provided
- All functions must be exported

## Setup

### Install NodeJS 12.11.x

In your home directory, run:

```bash
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
nodejs -v  # v12.11.1
npm -v     # 6.11.3
```

### Install Jest, Babel, and ESLint

In your project directory, install Jest, Babel, and ESLint using the supplied `package.json`:

```bash
npm install
```

### Configuration Files

Add the following configuration files to your project directory:

- **package.json**: Contains project metadata and dependencies.
- **babel.config.js**: Babel configuration file.
- **.eslintrc.js**: ESLint configuration file.

## Finally…

Don’t forget to run `npm install` from the terminal of your project folder to install all necessary project dependencies.
