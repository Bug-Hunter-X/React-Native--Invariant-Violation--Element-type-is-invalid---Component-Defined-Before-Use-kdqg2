# React Native: Invariant Violation: Element type is invalid - Component Defined Before Use

This repository demonstrates a common React Native error: `Invariant Violation: Element type is invalid`. This error arises when a component is used before it has been correctly defined or imported.  The example showcases the error and provides a solution.

## Problem:
The bug.js file demonstrates a scenario where a component is referenced before it's been properly imported or defined, leading to the 'Invariant Violation' error.  The error message specifically points to the problematic component.

## Solution:
The bugSolution.js file corrects the issue by ensuring that the component is imported and defined before being used in the render method.  Proper import order is crucial for avoiding this kind of error.

This simple example helps developers understand and prevent a frequently encountered problem in React Native development.