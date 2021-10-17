# The One And Only Buget Tracker
![Github licence](http://img.shields.io/badge/license-MIT-blue.svg)
## Description

> A progressive web app that a user will be able to add expenses and deposits to their budget with or without being connected online.

 ## Table of Contents 
  - [Description](#description)
  - [User Story](#user-story)
  - [Installation](#installation)
  - [Visual Demo](#visual-demo)
  - [Tests](#tests)
  - [Built With](#built-with)
  - [Acknowledgements](#acknowledgements)
  - [Author](#author)
  - [Contact](#contact)

## User Story
```
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling
```

## Installation

1. Download or clone repository
2. `npm install` to install the required npm packages to run

## Usage

App can be viewed [HERE](https://the-one-and-only-budgettracker.herokuapp.com/)

OR once you have cloned the Repo --->

* Application will be invoked by using the following command:

  `node server.js`

* Open your browser and go to
  
  `http://localhost:3000`

* User can add transactions as deposits or expenses by inputting the following:
  * Name of transaction
  * Transaction amount
  * For deposits - select **Add Funds**
  * For expenses - select **Subtract Funds**

* The total amount is reflected as soon as funds are entered

* The graph portrays the total funds over time by date entered for each transaction

<img src="assets\screenshot.JPG" alt= "Screenshot of budget tracker app">

* The app can be used online and offline

* Offline Functionality:
  * Enter deposits offline
  * Enter expenses offline

* When brought back online:
  * Offline entries should be added to tracker

## Tests

> There are no tests for this app.

## Built With

> [Visual Studio Code](https://code.visualstudio.com/)

## Acknowledgements

* [GitHub Pages](https://pages.github.com)
* [MDN Web Docs](https://developer.mozilla.org/en-US/)
* [NodeJS](https://nodejs.org/en/)
* [npm](https://www.npmjs.com/)
* [Express.js](https://expressjs.com/)
* [mongoose](https://mongoosejs.com/docs/)
* [Compression](https://www.npmjs.com/package/compression)

## Author

> Brenton Turnor - [https://github.com/BT134](https://github.com/BT134)

## Contact 

> Brenton Turnor [@BTurnor](https://twitter.com/BTurnor) - brenton.turnor@hotmail.com

> Profile: [https://bt134.github.io/bts-portfolio/](https://bt134.github.io/bts-portfolio/)
