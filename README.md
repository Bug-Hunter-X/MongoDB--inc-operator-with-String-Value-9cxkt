# MongoDB $inc operator with String Value
This example demonstrates an incorrect usage of MongoDB's `$inc` operator within an update operation. The `$inc` operator is used to increment a numerical field by a given value. However, in this case, a string is passed as the increment value which will lead to an error. 

The `bug.js` file contains the erroneous code, and `bugSolution.js` demonstrates the corrected approach using a numerical value. 

## Bug
The bug lies in passing a string value ('value') instead of a numeric value to the `$inc` operator.