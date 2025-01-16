# Dart Reduce Method Error Handling

This repository demonstrates a common error encountered when using the `reduce` method in Dart with empty lists.  The `reduce` method requires at least one element in the list. Attempting to use it on an empty list throws a `StateError`. This example showcases the error and provides a solution for safe usage.

## Error
The `bug.dart` file shows the error that occurs when you apply `reduce` to an empty list.

## Solution
The `bugSolution.dart` file provides a solution to prevent this error by adding a check for an empty list before applying `reduce`.