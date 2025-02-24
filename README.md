# Accessing HTML Element Before DOMContentLoaded

This repository demonstrates a common yet often overlooked error in JavaScript interacting with HTML elements: accessing elements before they have fully loaded into the Document Object Model (DOM).  The issue is that JavaScript executes before the entire HTML page is parsed and rendered. Attempting to access elements prematurely causes `null` values or other errors, hindering expected functionality.

The `bug.html` file showcases the problem, and the `bugSolution.html` file illustrates the correct approach using the `DOMContentLoaded` event listener.