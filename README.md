# PHP Array Modification with References: Unexpected Side Effects

This repository demonstrates a common issue in PHP related to array modification using references. When a function modifies an array passed by reference, the original array is altered, potentially causing unexpected behavior if the array is used elsewhere in the code. This example showcases the issue and offers a solution.

## Bug
The `bug.php` file contains code where a function modifies an array passed by reference. This results in the original array being unexpectedly modified.

## Solution
The `bugSolution.php` file provides a solution by creating a copy of the array before modification. This prevents unintended changes to the original array.