# React Native Context Error: Context value is undefined

This repository demonstrates a common error in React Native applications related to context usage: getting a context value of `undefined` when accessing context within a component.

## The Problem
The `useContext` hook attempts to retrieve a value from a context, but the context provider is missing in the parent component tree, resulting in an undefined value.

## Solution
Ensure that the context provider (`MyContextProvider` in this example) is properly wrapped around the components that need to access the context value.

## How to run
1. Clone the repository.
2. Navigate to the repository directory.
3. Run `npm install` to install dependencies.
4. Run `npx react-native run-android` or `npx react-native run-ios` to run the app on your device or emulator.

## Files
* `bug.js`: Demonstrates the error where context is not properly set up.
* `bugSolution.js`: Shows the corrected implementation with a properly provided context.
