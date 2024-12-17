# Julia Exponentiation Bug

This repository demonstrates an uncommon bug in Julia related to the exponentiation operator (`^`) when dealing with negative numbers.

The `myfunction` in `bug.jl` is designed to return the square of any number, regardless of its sign. However, due to how Julia handles exponentiation with negative bases and non-integer exponents, the result is not always as expected. This is because the function will return a complex number.