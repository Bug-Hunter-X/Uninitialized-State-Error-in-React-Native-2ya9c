# Uninitialized State Error in React Native

This repository demonstrates a common error in React Native development: accessing state before it's initialized.  The error occurs when trying to use a state variable within the component's render method before the constructor has finished setting the initial state.

## Problem
The `Bug.js` file shows a component that attempts to render a state variable (`count`) before the constructor has fully initialized it. This results in an undefined value which can lead to unexpected behavior or crashes.