# Incorrect Use of $inc Operator in MongoDB Update Query
This example demonstrates an incorrect usage of the `$inc` operator in a MongoDB update query. The `$inc` operator is used to increment a numerical field by a specified value, but in this case, the provided value is a string which will cause an error. 

## Bug
The bug is in using the `$inc` operator with a string value. The correct way is to use a number. 

## Solution
The solution is to provide a numerical value to the `$inc` operator instead of a string.