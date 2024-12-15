# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`.  The `BuggyArray.java` file contains code with this error, while `FixedArray.java` provides the corrected version. The issue stems from an incorrect loop condition when iterating over an array.  The loop accesses an element beyond the valid range of indices causing the exception.

**How to Reproduce:**

1. Compile `BuggyArray.java`.
2. Run the compiled code. Observe the `ArrayIndexOutOfBoundsException`.
3. Compile and run `FixedArray.java` to see the corrected behavior.