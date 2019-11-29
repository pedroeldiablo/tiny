# tiny
A tiny npm module

![npm (scoped)](https://img.shields.io/npm/v/@pedroeldiablo/tiny?style=for-the-badge)
![npm bundle size (scoped)](https://img.shields.io/bundlephobia/min/@pedroeldiablo/tiny?style=for-the-badge)

[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@pedroeldiablo/tiny?style=for-the-badge)](https://www.npmjs.com/package/@pedroeldiablo/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @bamblehorse/tiny
```

## Usage

```js
const tiny = require("@pedroeldiablo/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
