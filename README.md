# Unhandled Exception in Node.js HTTP Server

This repository demonstrates a common error in Node.js HTTP servers: unhandled exceptions.  Unhandled exceptions can cause the server to crash unexpectedly, leading to downtime and service interruptions.

The `bug.js` file contains a simple HTTP server with a flawed request handler.  The `bugSolution.js` file shows how to properly handle exceptions using try...catch blocks.

## How to reproduce the bug:

1.  Clone this repository.
2.  Navigate to the repository's directory.
3.  Run `node bug.js`.
4.  Observe that the server crashes when an error occurs in the request handler.

## How to fix the bug:

Refer to the `bugSolution.js` file for the corrected code.  The solution demonstrates how to use a try...catch block to handle potential errors in the request handler, preventing unexpected crashes.