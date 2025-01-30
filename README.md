# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical field by a specified value.  However, providing a non-numerical value results in an error.  This example showcases the error and provides a corrected solution.

## Error Description

The original code attempts to increment the `count` field with a string value, causing a MongoDB error.

## Solution

The corrected code uses a numerical value to correctly increment the field.