# F# Mutability Issue: Unexpected Results

This example demonstrates a common pitfall when working with mutable variables in F#. The `add` function calculates the sum of `x` and `y` only once, so changing those variables later doesn't update the result stored in `z`. 

The solution shows a functional approach using a function that recalculates the sum each time it's called.