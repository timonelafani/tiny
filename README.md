# @timonela/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@timonela/tiny.svg)](https://www.npmjs.com/package/@timonela/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@timonela/tiny.svg)](https://www.npmjs.com/package/@timonela/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @timonela/tiny
```

## Usage

```js
const tiny = require("@timonela/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
