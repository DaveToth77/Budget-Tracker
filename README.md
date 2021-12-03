# PWA Budget Tracker

![License Badge](https://img.shields.io/github/license/mmeii/progressive-budget-tracker) ![Top Language](https://img.shields.io/github/languages/top/mmeii/progressive-budget-tracker)

A Budget Tracker application that allows users to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

![Screen Shot 2021-12-03 at 10 47 29 AM](https://user-images.githubusercontent.com/85111342/144631629-bea03535-3d37-43a2-91b4-190057c4348c.png)

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Links](#Links)
* [Features](#Features)
* [License](#License)

## Installation

1. Download or clone repository
2. `npm install` to install the required npm packages to run

## Usage

* Application will be invoked by using the following command:

  `node server.js`

* Open your browser and go to
  
  `http://localhost:3001`

* User can add transactions as deposits or expenses by inputting the following:
  * Name of transaction
  * Transaction amount
  * For deposits - select **Add Funds**
  * For expenses - select **Subtract Funds**

* The total amount is reflected as soon as funds are entered

* The graph portrays the total funds over time by date entered for each transaction

  

* The app can be used online and offline

* Offline Functionality:
  * Enter deposits offline
  * Enter expenses offline

* When brought back online:
  * Offline entries should be added to tracker



## Links

* [Github](https://github.com/DaveToth77/Budget-Tracker)
* [Live Heroku App](https://agile-cove-62798.herokuapp.com/)

## Features

* Node
* Express
* JavaScript
* MongoDB
* Mongoose
* Progressive Web Application

## License

  
  Licensed under the [MIT](LICENSE) license.
