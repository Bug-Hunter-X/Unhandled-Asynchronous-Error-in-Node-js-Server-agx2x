# Unhandled Asynchronous Error in Node.js Server

This repository demonstrates a common issue in Node.js applications: unhandled errors during asynchronous operations. The provided `bug.js` simulates a server that randomly throws an error during request processing.  The solution (`bugSolution.js`) showcases how to gracefully handle such errors using proper error handling mechanisms.

## Running the Code

1. Clone the repository.
2. Navigate to the project directory.
3. Run `node bug.js` to see the error handling issue. Note the inconsistent behavior.
4. Run `node bugSolution.js` to see the robust solution that handles the errors consistently and prevents crashes.

## Bug Description

The `bug.js` file simulates a scenario where an asynchronous request might fail randomly. The absence of proper error handling in the asynchronous callback leads to inconsistent behavior and potential crashes if an error occurs.