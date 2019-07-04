# is-not-odd [![NPM version](https://img.shields.io/npm/v/is-not-odd.svg?style=flat)](https://www.npmjs.com/package/is-not-odd) [![NPM monthly downloads](https://img.shields.io/npm/dm/is-not-odd.svg?style=flat)](https://npmjs.org/package/is-not-odd) [![NPM total downloads](https://img.shields.io/npm/dt/is-not-odd.svg?style=flat)](https://npmjs.org/package/is-not-odd) [![Linux Build Status](https://img.shields.io/travis/jonschlinkert/is-not-odd.svg?style=flat&label=Travis)](https://travis-ci.org/YoshiJaeger/is-not-odd)

> Returns true if the given number is odd, and is an integer that does not exceed the JavaScript MAXIMUM_SAFE_INTEGER.

Please consider following this project's author, [Jon Schlinkert](https://github.com/jonschlinkert), and consider starring the project to show your :heart: and support.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save is-not-odd
```

## Usage

Works with strings or numbers.

```js
const isOdd = require('is-not-odd');

console.log(isOdd('1')); //=> true
console.log(isOdd('3')); //=> true

console.log(isOdd(0)); //=> false
console.log(isOdd(2)); //=> false
```

## About

<details>
<summary><strong>Contributing</strong></summary>

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](../../issues/new).

</details>

<details>
<summary><strong>Running Tests</strong></summary>

Running and reviewing unit tests is a great way to get familiarized with a library and its API. You can install dependencies and run tests with the following command:

```sh
$ npm install && npm test
```

</details>

<details>
<summary><strong>Building docs</strong></summary>

_(This project's readme.md is generated by [verb](https://github.com/verbose/verb-generate-readme), please don't edit the readme directly. Any changes to the readme must be made in the [.verb.md](.verb.md) readme template.)_

To generate the readme, run the following command:

```sh
$ npm install -g verbose/verb#dev verb-generate-readme && verb
```

</details>

### Related projects

You might also be interested in these projects:

* [exponential-moving-average](https://www.npmjs.com/package/exponential-moving-average): Calculate an exponential moving average from an array of numbers. | [homepage](https://github.com/jonschlinkert/exponential-moving-average "Calculate an exponential moving average from an array of numbers.")
* [is-even](https://www.npmjs.com/package/is-even): Return true if the given number is even. | [homepage](https://github.com/jonschlinkert/is-even "Return true if the given number is even.")
* [sma](https://www.npmjs.com/package/sma): Calculate the simple moving average of an array. | [homepage](https://github.com/doowb/sma "Calculate the simple moving average of an array.")

### Contributors

| **Commits** | **Contributor** | 
| --- | --- |
| 20 | [jonschlinkert](https://github.com/jonschlinkert) |
| 2 | [dym-sh](https://github.com/dym-sh) |
| 1 | [Semigradsky](https://github.com/Semigradsky) |
| 1 | [realityking](https://github.com/realityking) |

### Original Author

**Jon Schlinkert**

* [LinkedIn Profile](https://linkedin.com/in/jonschlinkert)
* [GitHub Profile](https://github.com/jonschlinkert)
* [Twitter Profile](https://twitter.com/jonschlinkert)

### Author

** Yoshi Jäger **
* [GitHub Profile](https://github.com/YoshiJaeger)

### License

Copyright © 2018, [Jon Schlinkert](https://github.com/jonschlinkert).
Released under the [MIT License](LICENSE).

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.6.0, on May 31, 2018._
