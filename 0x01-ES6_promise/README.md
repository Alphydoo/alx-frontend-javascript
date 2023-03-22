# 0x01. ES6 Promises

## Resources
* Promise
* JavaScript Promise: An inttroduction
* Await
* Async
* Throw/Try

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

* Promises (how, why, and what)
* How to use the then, resolve, catch methods
* How to use every method of the Promise object
* Throw / Try
* The await operator
* How to use an async function

## Files

### [0. Keep every promise you make and only make promises you can keep](./0-promise.js)
* Return a Promise using this prototype function getResponseFromAPI()

### [1. Don't make a promise...if you know you can't keep it](./1-promise.js)
* Using the prototype below, return a promise. The parameter is a boolean.

### [2. Catch me if you can!](./2-then.js)
* Using the function prototype below

function handleResponseFromAPI(promise)
Append three handlers to the function:

When the Promise resolves, return an object with the following attributes
status: 200
body: success
When the Promise rejects, return an empty Error object
For every resolution, log Got a response from the API to the console

### [3. Handle multiple successful promises](./3-all.js)
* In this file, import uploadPhoto and createUser from utils.js

Knowing that the functions in utils.js return promises, use the prototype below to collectively resolve all promises and log body firstName lastName to the console.
