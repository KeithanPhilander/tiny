
# @keithan/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@keithan/tiny.svg)](https://www.npmjs.com/package/@keithan/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@keithan/tiny.svg)](https://www.npmjs.com/package/@keithan/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @keithan/tiny
```

## Usage

```js
const tiny = require("@keithan/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```