#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Runtime complexity: O(n), n is increasing linearly with a single step.


b) Runtime complexity: O(1) even though there is a second loop, the second loop is not re-iterating over n, it is only using it as a comparison.


c)Runtime complexity is O(n) because you are returning a constant value and not looping over anything even if you are recursing a single time.

## Exercise II


start the test from the middle floor and see if the egg is broken or not. if it is move down to the lower half of the buliding and start test from the middle floor of lower half, if not move up to the higher half and start test from the middle floor of higher half. Repeat until find the line of broken and not broken