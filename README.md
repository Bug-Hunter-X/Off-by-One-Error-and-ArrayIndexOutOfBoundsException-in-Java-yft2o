# Off-by-One Error and ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java error: an off-by-one error in a loop, leading to an `ArrayIndexOutOfBoundsException`.  The `bug.java` file contains the buggy code, while `bugSolution.java` shows the corrected version.

**Bug:** The for loop iterates one time too many, causing an `ArrayIndexOutOfBoundsException`. The `println` statement attempts to access an element beyond the array's bounds.

**Solution:** The loop condition is changed to `i < array.length` to prevent accessing the element at index 5, which is out of bounds for an array of size 5.