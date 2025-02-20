# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers: missing error handling for invalid input.  The provided `bug.js` file shows a route that attempts to parse a user ID as an integer without checking for errors.  This can lead to unexpected behavior or crashes if the ID is not a valid integer.

The solution, `bugSolution.js`, demonstrates proper error handling by validating the user ID before parsing it and handling the case where the user is not found.