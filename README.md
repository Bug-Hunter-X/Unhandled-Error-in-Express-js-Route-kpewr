# Unhandled Error in Express.js Route

This repository demonstrates a common error in Express.js applications: the lack of proper error handling when dealing with user input or database queries.

The `bug.js` file contains the erroneous code, where the route handler for `/users/:id` doesn't check for the validity of the `userId` before attempting to fetch the user from the database.

The `bugSolution.js` file shows the corrected code with robust error handling that prevents application crashes and provides informative error responses to clients.