[![Build Status](https://travis-ci.org/pelevesque/wrap-number.svg?branch=master)](https://travis-ci.org/pelevesque/wrap-number)
[![Coverage Status](https://coveralls.io/repos/github/pelevesque/wrap-number/badge.svg?branch=master)](https://coveralls.io/github/pelevesque/wrap-number?branch=master)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

# wrap-number

Wraps a number inside a range.

## Node Repository

https://www.npmjs.com/package/@pelevesque/wrap-number

## Installation

`npm install @pelevesque/wrap-number`

## Tests

Command                      | Description
---------------------------- | ------------
`npm test` or `npm run test` | All Tests Below
`npm run cover`              | Standard Style
`npm run standard`           | Coverage
`npm run unit`               | Unit Tests

## Usage

```js
const wrapNumber = require('@pelevesque/wrap-number')
```

```js
const num = 11
const rangeMin = -10
const rangeMax = 10
const result = wrapNumber(num, rangeMin, rangeMax)
// result === -10
```
