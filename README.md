# ServerTime - Package

A simple package that outputs the time of a node.js server in specific format

## Table of Contents

- [General Info](#General-Info)
- [Technologies](#Technologies)
- [Setup](#Setup)
- [Using](#Using)
- [Status](#Status)

## General Info

This started as a test using Javascript dateTime module.
Has been setup in standalone package for my other projects to use.
Format is `HH:MM:SS DD(st/nd/rd/th) of MM YYYY`
## Technologies

Uses the Javascript `dateTime` module

## Setup

1. Run `npm install dMacGit/ServerTime` to manually add the package. 
**OR**
Simply add this package to your dependancies lisk in package.json file then Run `npm install` or `npm clean-install`
``` json 
//Config to add into your package.json file
"dependencies": {
    "myServerTime": "github:dMacGit/ServerTime"
}
```
2. Import it as a package in your app.js file or equivalent main.js file
``` javascript
const constName = require('myServerTime')
```

## Using

This can be used in either of two ways:
1. Calling `generateTime()` which generates a dateTime object, then passes it to the `formatTime()`
function to return it in a readable format. 

2. Calling `formatTime()` directly and passing it in a `dateTime` object.

## Status 

- ### __Complete__

This project is complete, and not under further develeopment.