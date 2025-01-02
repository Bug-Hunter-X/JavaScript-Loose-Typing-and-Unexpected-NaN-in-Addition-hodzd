# JavaScript Loose Typing Bug

This repository demonstrates a common JavaScript bug related to loose typing and the unexpected NaN (Not a Number) result when adding numbers and undefined values.

## Bug Description

The `foo` function adds two numbers. When the second argument is `undefined`, the result is unexpectedly `NaN` instead of the expected numerical result.

## Solution

The solution involves adding explicit type checking or using a default value for undefined parameters to avoid type coercion issues.