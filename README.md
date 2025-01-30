# F# Mutable Variable and Function Scope Issue

This example demonstrates a common misunderstanding involving mutable variables and function scope in F#.

The `add` function calculates the sum of `x` and `y`.  However, changing `x` and `y` after calling `add` does not affect the initial value of `z` because `add` creates a copy of values rather than a reference.