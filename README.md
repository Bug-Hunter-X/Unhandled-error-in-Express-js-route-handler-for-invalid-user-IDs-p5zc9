# Express.js Route Handler Error

This repository demonstrates a common error in Express.js route handlers:  failure to handle invalid input gracefully.  The `bug.js` file shows a route that attempts to parse a user ID as an integer without error handling. This can lead to unexpected behavior or crashes if the ID isn't a valid integer.

The `bugSolution.js` file provides a corrected version with robust error handling, demonstrating best practices for handling potential errors in Express.js routes.