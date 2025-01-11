# Objective-C NSDecimalNumber Precision Bug

This repository demonstrates a subtle bug related to precision loss when using `NSDecimalNumber` in Objective-C.  The bug arises when initializing `NSDecimalNumber` objects from strings with many decimal places.  Rounding errors can accumulate, leading to unexpected results in calculations.

The `bug.m` file shows the problematic code, and `bugSolution.m` presents a solution involving careful handling of precision and rounding.