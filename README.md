# Team Profile Generator

## Description

The profile generator generates an HTML file that holds professional teams with their employer's information which is displayed as a cards. The acceptable user input allows you to identify the employee's postion, id number, email, as well as the office number for managers, the GitHub username linked to his/her profile for engineers, and the attending school for interns.
This application does those things by using node.js, along with inquirer and jest, to generate an HTML based on the informated taken in by the user. HTML file is generated into the dist folder where there is a CSS file that's linked for styling purposes.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [How to Contribute](#how-to-contribute)
- [Tests](#tests)

## Installation

This application has dependencies: inquirer and jest.

1. Make sure you have Node.js installed on your computer. 
2. Clone the repository for use.
3. Next, we will install the above mentioned packages using npm (node package manager).
4. First, using the CLI, run npm init to install a package.json and personalize your application.
5. If you want to use a .gitignore to keep unnecessary data out of your GitHub repo, make sure your gitignore includes: node_modules; package-lock.json; .vscode; .DS_Store/; .history; make sure this file exists before installing inquirer and jest.
6. To install inquirer, run the command: npm i inquirer@8.2.4 -- this applicaiton does require that specific version of inquirer.
7. To install jest, use the command: npm i jest.
8. To run tests --> command: npm run test
9. To start the application and generate your team's HTML file, use command: node index
10. Following these steps, you should be able to run the app smoothly and successfully!

## Usage

Instructions are listed above. Refer to screenshots for demo of application and tests.

https://drive.google.com/file/d/17JX5IxqfFoUX1fUDUeiKgCVowgTLZcFO/view?usp=sharing

![html screenshot](./images/Screenshot%202023-06-02%20at%206.13.32%20PM.png)

![testing screenshot](./images/Screenshot-test.png)

## Credits

Multiple TA's have helped me with this project.

Technologies used: JavaScript, Node.js, Inquirer, Jest, Path, HTML, CSS

## License

No license used.

## How to Contribute

If you would like to contribute please don't hesitate to contact me.

## Tests

There are test files utilitzed with Jest. The test is ran for classes for Employee, Manager, Engineer, and Intern.