# Unhandled JS Exception: Cannot read properties of undefined (reading 'property') in React Native

This repository demonstrates a common React Native error and its solution. The error occurs when attempting to access a property of an object that is null or undefined, often due to asynchronous data fetching or component mounting before data is ready.

## The Bug
The `bug.js` file contains code that attempts to render user data before it's loaded. This leads to the `Cannot read properties of undefined` error.

## The Solution
The `bugSolution.js` file demonstrates how to prevent this error using optional chaining (`?.`) and nullish coalescing (`??`). These operators provide a safe way to access properties and provide default values when the object is null or undefined.  Conditional rendering is also shown as an alternative approach.