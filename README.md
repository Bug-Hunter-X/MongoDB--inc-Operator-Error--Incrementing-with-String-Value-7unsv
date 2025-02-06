# MongoDB $inc Operator Error
This repository demonstrates an example of an uncommon error in MongoDB related to the $inc operator.  The error arises from attempting to increment a numeric field using a string value. This leads to unexpected behavior and potential data corruption.

The `bug.js` file shows the incorrect implementation.  The `bugSolution.js` file shows the correct implementation.

## Bug Description
The provided code incorrectly attempts to increment the `count` field of a document in the `myCollection` collection with a string value. The `$inc` operator only works with numeric values.