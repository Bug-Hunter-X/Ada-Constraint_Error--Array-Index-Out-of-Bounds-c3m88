# Ada Constraint_Error Example

This repository demonstrates a common error in Ada programming: attempting to access an array element outside its defined bounds.  The `bug.ada` file contains code that will raise a `Constraint_Error` exception.  The `bugSolution.ada` file shows how to prevent this error using range checks and improved array handling.

## How to reproduce the error:
1. Compile `bug.ada` using an Ada compiler (like GNAT).
2. Run the compiled executable.
3. Observe the `Constraint_Error` exception.

## How to fix the error:
Refer to `bugSolution.ada` for a corrected version of the code.  The key is to always ensure that array indices remain within the valid range.  Ada's range checks help prevent these errors during compilation or runtime.