# Incorrect DOM Manipulation in HTML

This repository demonstrates a common error in JavaScript when interacting with the HTML DOM. The code attempts to access and modify an HTML element's content without using the proper method of obtaining a reference to the element.  The solution shows the correct way of doing this.

## Bug
The `bug.html` file contains the erroneous code. It tries to change the content of a div with the id "myDiv" directly without using `document.getElementById()`. This will result in a `ReferenceError` because `myDiv` is not defined in the global scope.

## Solution
The `bugSolution.html` file provides the corrected code. It uses `document.getElementById()` to correctly obtain a reference to the div before modifying its content.