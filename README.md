# F# Mutable Variable Swap Bug

This repository demonstrates a common issue in F# involving mutable variables and unexpected behavior when attempting to swap their values.

The `bug.fs` file contains code that attempts to swap two mutable variables using a function. However, due to the way mutable variables are handled in F#, the result is not as expected.

The `bugSolution.fs` file provides a corrected version that uses a different approach to achieve the intended swap operation.

This example highlights the importance of understanding how mutable variables behave in F# to avoid potential errors in your code.