# Redux ECommerce Store Refactor
You can view my Redux ECommerce Store Refactor here: [Redux Ecommerce Store Refactor](https://mern-shopping-lh.herokuapp.com/)

## Table of Contents

- [Description](#description)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Features](#features)
- [Improvements](#improvements)
- [Tests](#tests)


## Description

This is a refactoring project to updated the code for a React MERN ECommerce Shop to utilise React Redux. Formerly the code uses React's useReducer, createContext and useContext Hook Methods to pass props data. Refactoring this using Redux allows the data to be accessed in globally by prop drilling instead of threading, that is, passing information down hierarchically through multiple components with props.


## Technologies

Technologies used in this portfolio include:
 * HTML
 * CSS
 * JS/ES6
 * React
 * NodeJS and npm packages
    * Global
        * concurrently (run npm i concurrently before npm run install)
    * Client
        * react (npx-create-react-app)
        * react-redux
        * redux
    * Server 
    * apollo-server-express version "^2.11.0"
        * The app won't work with the latest version due to how it handles middleware functions differently. Install version 2.x...
    * bcrypt
    * dotenv
    * express
    * graphql
    * jsonwebtoken
    * mongoose
    * nodemon
    * stripe


## Usage

My portfolio should look like this, please do not recreate or reuse under any circumstances without permission:

 ![App Screenshot1](screenshots/screenshot1.png)
 ![App Screenshot2](screenshots/screenshot2.png)
 ![App Screenshot3](screenshots/screenshot3.png)
 ![App Screenshot4](screenshots/screenshot4.png)


## Credits

Project refactored by Leon Hsu[leonhsu95]. Copyright 2021 Leon Hsu leonhsu95.

## License

Licensed under the [MIT](https://opensource.org/licenses/MIT).

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Features

- eCommerce website works as expected of a dropship website where you can make online purchases.
- Stripe handles online transactions. As this is in sandbox mode, feel free to insert 4242 4242 4242 as the test billing Visa Card and any 3 CVC digit and a future date to test payment gateway.

## Improvements
- Creating a user exists page would be could for UX when the user signs up to the page with preexisting credentials.

## Tests

Website is validated with:
- [HTML Markup Validation Tool](https://validator.w3.org/)
- [CSS Validation Service](https://jigsaw.w3.org/css-validator/)
- [JS Validation Service](https://jshint.com/)
- [JWT.IO](https://jwt.io/) to check JWT tokens credential
- [Robo 3T](https://robomongo.org/) for MongoDB database management
- React's Strict Mode enabled
- React's Jest Test Suite 