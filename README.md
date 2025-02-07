# Uncommon HTML Bug: Accessing Non-Existent Element

This repository demonstrates a subtle bug in HTML where trying to access and modify the `innerHTML` property of an element that does not yet exist in the DOM results in a runtime error.  This is often missed during development and can lead to unexpected application behavior.

The `bug.html` file showcases the error.  The `bugSolution.html` file presents a corrected version. The key is to ensure the element exists before attempting to manipulate its content.