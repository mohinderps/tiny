### Removes all spaces from a string

## Install

```shell
npm install @mohindersaluja/tiny
```

## Usage

````shell
const tiny = require("@mohindersaluja/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1```
````
