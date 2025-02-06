# Uncommon HTML Error: Accessing Non-Existent NodeList Property

This repository demonstrates an uncommon error in HTML that can occur when interacting with NodeLists returned by methods like `document.querySelectorAll()`.  Attempting to access a property that does not exist on the NodeList itself (as opposed to a property of the individual nodes within the NodeList) will likely not throw an error but may result in unexpected behavior.

The `bug.html` file shows the problematic code, while `bugSolution.html` presents a corrected approach.