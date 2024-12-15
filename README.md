# Uncommon HTML Bug: Typo in getElementById

This repository demonstrates a subtle bug that can be difficult to track down.  The core issue is a simple typo in the JavaScript code that prevents an HTML element from being updated.

## Bug Description
The `bug.html` file contains a `div` element that should be modified by a JavaScript script.  However, due to a typo in the `getElementById` function call, the script fails silently without any error messages.  This can make debugging significantly harder.

## Solution
The `bugSolution.html` file provides the corrected code with the proper `getElementById` function call, showing how to successfully update the `div` element's content.