# CSS Pseudo-element Content Overflow Bug

This repository demonstrates a common CSS bug involving pseudo-elements and long strings.  The bug occurs when the content of a `::before` or `::after` pseudo-element exceeds the dimensions of its parent container.  This can lead to unexpected visual results, affecting layout and overall design.

The `bug.css` file contains the problematic CSS, while `bugSolution.css` provides a solution.

## Solution

The solution involves using techniques to handle the overflow, such as `text-overflow`, `overflow`, or limiting the text length.  The specific solution depends on the desired behavior.