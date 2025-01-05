# JavaScript TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common JavaScript error: `TypeError: Cannot read properties of undefined (reading 'length')`.  This error occurs when you try to access the `length` property of a variable that holds the value `undefined`.

The `bug.js` file contains the buggy code.  The `bugSolution.js` file provides the corrected version.

## How to Reproduce

1. Clone this repository.
2. Navigate to the repository's directory.
3. Run `node bug.js` in your terminal. You should see the error.
4. Run `node bugSolution.js` to see the corrected output.

## Solution

The solution involves adding a check to handle the `undefined` case before attempting to access the `length` property.  This prevents the `TypeError` from being thrown.