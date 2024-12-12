# JavaScript Loose Comparison Pitfall
This repository demonstrates a common JavaScript error stemming from the use of loose equality (`==`) when comparing values, specifically `null` and `undefined`.  Loose comparison can lead to unexpected behavior and subtle bugs.

The `bug.js` file showcases the problematic code, while `bugSolution.js` offers a corrected version using strict equality (`===`).

## How to reproduce
1. Clone this repository.
2. Open `bug.js` and run it using Node.js (or a browser console).
3. Observe the unexpected result when calling the function with `undefined`.
4. Compare this with the output of `bugSolution.js` to understand the fix.

## Lesson learned
Always prefer strict equality (`===`) over loose equality (`==`) in JavaScript to avoid unexpected type coercion and ensure accurate comparisons.