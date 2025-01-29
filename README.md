# React 19 useEffect Hook Misuse
This repository demonstrates a common error in React 19 applications involving the useEffect hook, specifically when handling asynchronous operations and neglecting proper error handling and cleanup.

## Bug Description
The `bug.js` file showcases an incorrect implementation of useEffect where the promise from the fetch call is not properly handled.  This can lead to unhandled errors or unexpected behavior.

## Solution
The `bugSolution.js` file provides a corrected implementation with error handling and cleanup for the useEffect hook, preventing unexpected behavior.