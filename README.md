# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numerical field by a specified value. However, providing a string value instead of a number will cause an error.

## Bug Description
The provided code attempts to increment the `field` by '1' (string).  This will cause an error because `$inc` requires a numerical value.

## Solution
The corrected code uses the number 1 instead of the string '1' to increment the field correctly.