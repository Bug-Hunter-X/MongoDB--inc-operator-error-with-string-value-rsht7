# MongoDB $inc operator error with string value
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The error arises from using a string value instead of a numeric value with the `$inc` operator. The `$inc` operator is designed to increment a numeric field by a specified amount, and providing a string will lead to an error.

The `bug.js` file contains the erroneous code, while `bugSolution.js` provides the correct implementation.
