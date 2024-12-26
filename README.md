# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java programming error: the `ArrayIndexOutOfBoundsException`. The `bug.java` file contains code that attempts to access an array element beyond its valid index range, resulting in this exception.

The `bugSolution.java` file provides a corrected version of the code, showing how to avoid this error.

## How to reproduce the bug

1. Compile `bug.java` using a Java compiler.
2. Run the compiled code. You will see an `ArrayIndexOutOfBoundsException`.

## How to fix the bug

Refer to the `bugSolution.java` file for the corrected code.  The solution involves carefully checking array indices before accessing elements to ensure that they are within the valid range (0 to array.length -1).
