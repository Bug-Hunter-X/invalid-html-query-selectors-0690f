# Incorrect querySelector Usage in HTML

This repository demonstrates a common mistake when using the `querySelector` method in JavaScript within an HTML file. The error occurs when attempting to select an element by its ID using a period (`.`) instead of a hash symbol (`#`).

## The Bug

The `bug.html` file contains JavaScript code that tries to access a div element by its ID using an incorrect selector (".myDiv").  This selector is looking for an element with class "myDiv", not an element with id "myDiv". As a result, the script fails to update the div's content.

## The Solution

The `bugSolution.html` file demonstrates the correct way to access the element using the `#` symbol for ID selection. This ensures the script successfully modifies the content of the div element.

## How to Reproduce the Bug

1. Clone this repository.
2. Open `bug.html` in your web browser.
3. Observe that the div with id "myDiv" remains empty.

## How to Fix the Bug

1. Replace the incorrect selector (".myDiv") with the correct selector ("#myDiv") in the JavaScript code.
2. Re-run `bugSolution.html` to see the corrected output.
