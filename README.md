# tiny
A tiny npm module

![npm (scoped)](https://img.shields.io/npm/v/@pedroeldiablo/tiny?style=for-the-badge)
![npm bundle size (scoped version)](https://img.shields.io/bundlephobia/min/@pedroeldiablo/tiny/2.0.0?style=for-the-badge)

Removes all spaces from a string.

## Install

```
$ npm install @pedroeldiablo/tiny
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
