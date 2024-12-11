# Unexpected Width Calculation with Fractional Widths in Flex Containers with Padding
This repository demonstrates a bug in Tailwind CSS where fractional width classes (like `w-1/2`) don't work as expected inside flex containers that also have padding.

The issue is that the padding seems to interfere with the width calculation, resulting in unexpected layout behavior.

## Steps to Reproduce
1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe that the red and blue divs do not occupy exactly half of the container's width due to padding causing incorrect width calculation.

## Solution
The `solution.html` file demonstrates a fix by explicitly specifying widths using percentages or by removing the padding from the parent element.