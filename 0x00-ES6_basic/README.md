# Project: 0x00. ES6 Basics

![Node_JS](./main-files/arrow-functions.png)

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=900&size=32&pause=1000&width=435&lines=ES6+Basic\(:)](https://git.io/typing-svg)

> This document outlines the tasks for the ES6 Basics project, which is part of the ALXSE short specializations curriculum focused on modern JavaScript, particularly ECMAScript 6 (ES6).

![Arrow Functions](./main-files/node_js-img.png)

## Resources
- https://github.com/mbeaudru/modern-js-cheatsheet
- https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics
- https://darrenderidder.github.io/talks/ModulePatterns/#/14
- https://www.youtube.com/watch?v=sjyJBL5fkp8
- https://www.youtube.com/watch?v=vZBCTc9zHtI
- https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics
- https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Classes_in_JavaScript
- https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object_prototypes
- https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Classes_in_JavaScript
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures
- https://alistapart.com/article/getoutbindingsituations/

  ## Software lINTER
  Software Linter
Definition
A software linter also known as a “linter” is a tool used to identify and report potential issues (syntax errors, undeclared variables, etc.) in a program. It can even report convention or style inconsistencies. It does so by highlighting them so that the programmer is aware, so changes can be made. There are a wide variety of linters as well as lint rules for specific programming languages and even for software frameworks.

There are typically two ways to lint code:

Actively
Passively
Active
Active checking is typically achieved by running a monitor tool that is constantly checking the file that your working on in order to spot inconsistencies and possible errors (e.g., having a specific linter along with some lint rules installed as a plug-in in your Code Editor).

Passive
Passive checking is done by taking a piece of code, and manually running it through a tool to identify potential issues. For example, copying and pasting your code into a specific linter tool, or running the linter against a specific file using the command line. This tool can be installed locally or be available as a service (e.g., website on the Internet).

Examples
Screenshot of an active linter pycodestyle (Python) integrated into Visual Studio Code 
- https://intranet.alxswe.com/rltoken/OcBbDM8QALAmJA4iwFjGBA
- https://intranet.alxswe.com/rltoken/Or1sNv7iTj-qzebPqIT2Ig
- https://intranet.alxswe.com/rltoken/SwEhYt8xBLP0tYRzYrb6Rg

### Read or watch:-

- [ECMAScript 6 - ECMAScript 2015](https://www.w3schools.com/js/js_es6.asp)

- [Statements and declarations](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements)

- [Arrow functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)

- [Default parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters)

- [Rest parameter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters)

- [Javascript ES6 — Iterables and Iterators](https://towardsdatascience.com/javascript-es6-iterables-and-iterators-de18b54f4d4)

## Task Overview

- **Task 0: Const or let?**

  - Objective: Modify the taskFirst and taskNext functions to use const and let instead of var.
  - Key Concepts: Understanding the difference and appropriate usage of const and let.

- **Task 1: Block Scope**

  - Objective: Modify the taskBlock function to ensure variables aren't overwritten inside the conditional block.
  - Key Concepts: Mastery of block scoping and the scope differences between var, let, and const.

- **Task 2: Arrow Functions**

  - Objective: Rewrite a standard function to use ES6’s arrow syntax.
  - Key Concepts: Converting traditional functions to arrow functions and understanding their benefits.

- **Task 3: Parameter Defaults**

  - Objective: Condense a function to use default parameters.
  - Key Concepts: Implementing and understanding default parameters in functions.

- **Task 4: Rest Parameter Syntax for Functions**

  - Objective: Modify a function to return the number of arguments passed to it using the rest parameter syntax.
  - Key Concepts: Understanding and using rest parameters in functions.

- **Task 5: The Wonders of Spread Syntax**

  - Objective: Use spread syntax to concatenate arrays and strings.
  - Key Concepts: Mastering the spread operator for arrays and strings.

- **Task 6: Take Advantage of Template Literals**
  - Objective: Rewrite a function to use template literals.
  - Key Concepts: Utilizing template literals for cleaner and more readable string concatenation.

- **Task 7: Object Property Value Shorthand Syntax**

  - Objective: Modify a function to use object property value shorthand.
  - Key Concepts: Simplifying object property assignments with ES6 shorthand syntax.

- **Task 8: No Need to Create Empty Objects Before Adding in Properties**

  - Objective: Rewrite getBudgetForCurrentYear to use ES6 computed property names.
  - Key Concepts: Using computed property names in object creation.

- **Task 9: ES6 Method Properties**

  - Objective: Update getFullBudgetObject to use ES6 method properties.
  - Key Concepts: Converting object methods to ES6 method property syntax.

- **Task 10: For...of Loops**

  - Objective: Rewrite appendToEachArrayValue to use ES6’s for...of operator.
  - Key Concepts: Implementing and understanding for...of loops.

- **Task 11: Iterator**

  - Objective: Write createEmployeesObject function to create an object with a specific format.
  - Key Concepts: Understanding and creating iterators.

- **Task 12: Let's Create a Report Object**

  - Objective: Write createReportObject to organize data into a specific structure.
  - Key Concepts: Advanced object manipulation and report generation.

## Tasks

| Task | File |
| ---- | ---- |
| 0. Const or let? | [0-constants.js](./0-constants.js) |
| 1. Block Scope | [1-block-scoped.js](./1-block-scoped.js) |
| 2. Arrow functions | [2-arrow.js](./2-arrow.js) |
| 3. Parameter defaults | [3-default-parameter.js](./3-default-parameter.js) |
| 4. Rest parameter syntax for functions | [4-rest-parameter.js](./4-rest-parameter.js) |
| 5. The wonders of spread syntax | [5-spread-operator.js](./5-spread-operator.js) |
| 6. Take advantage of template literals | [6-string-interpolation.js](./6-string-interpolation.js) |
| 7. Object property value shorthand syntax | [7-getBudgetObject.js](./7-getBudgetObject.js) |
| 8. No need to create empty objects before adding in properties | [8-getBudgetCurrentYear.js](./8-getBudgetCurrentYear.js) |
| 9. ES6 method properties | [9-getFullBudget.js](./9-getFullBudget.js) |
| 10. For...of Loops | [10-loops.js](./10-loops.js) |
| 11. Iterator | [11-createEmployeesObject.js](./11-createEmployeesObject.js) |
| 12. Let's create a report object | [12-createReportObject.js](./12-createReportObject.js) |

---

### Environment

- Language: JavaScript
  - Node Version: 12.11.1
  - OS: Ubuntu 20.04 LTS
  - Style guidelines:
    - [Javascript Semistandard](https://github.com/standard/semistandard) `sudo npm install semistandard --global`
    - [Eslint Standard](https://eslint.org/) `npx eslint nameoffile.js`
  - [Install Semistandard - Note](../0x12-javascript-warm_up/README.md)
    - [Airbnb Javascript Style Guide](https://github.com/airbnb/javascript)

---
