# 0x04. TypeScript Project

## Resources
Read or watch:
- [TypeScript in 5 minutes](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)
- [TypeScript documentation](https://www.typescriptlang.org/docs/)

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
- Basic types in TypeScript
- Interfaces, Classes, and functions
- How to work with the DOM and TypeScript
- Generic types
- How to use namespaces
- How to merge declarations
- How to use an ambient Namespace to import an external library
- Basic nominal typing with TypeScript

## Requirements
- Allowed editors: `vi`, `vim`, `emacs`, `Visual Studio Code`
- All your files should end with a new line
- All your files will be transpiled on Ubuntu 18.04
- Your TS scripts will be checked with Jest (version 24.9.*)
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should use the `.ts` extension when possible
- The TypeScript compiler should not show any warning or error when compiling your code

## Configuration Files
Please use the following files for the project:
- `package.json`
- `.eslintrc.js`
- `tsconfig.json`
- `webpack.config.js`

## Tasks

### 0. Creating an Interface for a Student (Mandatory)

1. Copy the provided configuration files into the `task_0` directory:
   - `package.json`
   - `.eslintrc.js`
   - `tsconfig.json`
   - `webpack.config.js`

2. Write your code in the `main.ts` file:
   - Write an interface named `Student` that accepts the following elements:
     - `firstName` (string)
     - `lastName` (string)
     - `age` (number)
     - `location` (string)
   - Create two students and create an array named `studentsList` containing the two variables.
   - Using Vanilla JavaScript, render a table and for each element in the array, append a new row to the table.
   - Each row should contain the first name of the student and the location.

