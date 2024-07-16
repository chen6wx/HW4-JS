# Homework 3 Javascript

## What is the difference between instance methods and static methods?

Instance methods require an instance of the class to be called while static methods does not have that requirement.

## How does Javascript handle concurrency?

Javascript handles concurrency mainly through asynchronous operations. JavaScript also has an event loop that allows it to maintain multiple operations on a single thread.

## What is async/await? How does it differ from using the promise instance methods?

Async/ await are methods in JavaScript that allow asynchronous methods to be behave synchronously. Await is used within async methods to pause until a promise is fulfilled. Promises use nested then catch to allow operations to be executed sequentially.

## Can you use await outside of an async function?

No, await must be used inside of an async function.

## What is callback hell and why is it considered a problem?

Callback hell is when there are multiple nested callback functions that makes the code difficult to interpret due to the complexity. This makes it hard to decipher what the code is supposed to do and to debug potential errors that may occur.