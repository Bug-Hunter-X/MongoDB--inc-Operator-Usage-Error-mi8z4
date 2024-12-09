# MongoDB $inc Operator Usage Error
This example demonstrates an incorrect usage of the `$inc` operator in a MongoDB update query. The `$inc` operator is used to increment a numerical field by a specified value. However, in the given code, the increment value is provided as a string, which leads to an error. The correct way to use the `$inc` operator is to provide a numerical value for the increment.

**Bug:** The `$inc` operator is passed a string value instead of a number. This will result in an error.  The correct usage should be a numerical value.

**Solution:** The solution involves changing the increment value to a number.  The updated code will correctly increment the counter.