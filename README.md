# Unexpected Behavior of Mutable Variable Swap in F#

This example demonstrates a common misunderstanding in F# when working with mutable variables and functions.  Due to F#'s pass-by-reference semantics for mutable variables, a seemingly straightforward swap function doesn't behave as intuitively expected.

The `bug.fs` file contains code that attempts to swap two mutable variables, but fails due to the pass-by-reference nature of mutable variables in F#.

The `bugSolution.fs` file provides a corrected version which showcases the correct way to handle the swapping of mutable variables.

This example highlights the importance of understanding how mutability and function parameters interact in F# to avoid unexpected behavior.