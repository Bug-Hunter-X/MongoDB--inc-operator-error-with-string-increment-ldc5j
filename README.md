# MongoDB $inc operator error with string increment
This code demonstrates an error that occurs when using the MongoDB $inc operator with a string value instead of a number.  The $inc operator is designed to increment a numerical value by a specified amount. Attempting to increment a field by a string will result in an error.

The `bug.js` file demonstrates the incorrect usage of the $inc operator, while `bugSolution.js` provides a corrected version.