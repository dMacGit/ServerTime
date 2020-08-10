# ServerTime - Package

A simple package that outputs the time of a node.js server in specific format

## Table of Contents

- [General Info](#General-Info)
- [Technologies](#Technologies)
- [Setup](#Setup)
- [Future](#Future)
- [Status](#Status)

## General Info

This started as a test using Javascript dateTime module.
Has been setup in standalone package for my other projects to use.
Format is `HH:MM:SS DD(st/nd/rd/th) of MM YYYY`
## Technologies

Uses the Javascript `dateTime` module

## Setup

Info to come.

## Using

This can be used in either of two ways:
1. Calling `generateTime()` which generates a dateTime object, then passes it to the `formatTime()`
function to return it in a readable format. 

2. Calling `formatTime()` directly and passing it in a `dateTime` object.

## Status 

- ### __Complete__

This project is complete, and not under further develeopment.