![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## 00-Deployment

### Author: Brent Woodward

### Links and Resources
* [![Build Status](https://travis-ci.com/BrentTech/00-deployment.svg?branch=master)](https://travis-ci.com/BrentTech/00-deployment)
* [repo](https://github.com/BrentTech/00-deployment)
* [travis](https://travis-ci.com/BrentTech/00-deployment)
* [heroku](https://woodward-00-deployment.herokuapp.com/)

### Modules
#### `pol.js`
##### Exported Values and Methods
* `isAlive()`
* Returns true or false
  *false if a parameter is sent

### Setup
#### `.env` requirements
* `PORT` - defined in the environment

#### Running the app
* `npm start`
* Endpoint: `/`
  * Returns `true`

#### Tests
* npm test (runs unit tests)
* npm run lint (runs linter tests)
