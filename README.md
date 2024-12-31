# Unexpected calc() Behavior in CSS Width Calculation

This repository demonstrates a bug encountered when using the `calc()` function in CSS to calculate the width of an element based on the viewport width. The calculated width is not what is expected.

## Bug Description

The `calc()` function in CSS is used to perform calculations. However, in this case, the calculation results in an unexpected width.

## Bug Reproduction

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe that the width of the element is not what's expected based on the viewport width.

## Solution

The solution involves ensuring that the units used in the `calc()` expression are consistent and the calculation is correct.

See `bugSolution.css` for a corrected implementation.