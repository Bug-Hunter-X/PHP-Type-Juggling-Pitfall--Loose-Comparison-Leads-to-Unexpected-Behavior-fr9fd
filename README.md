# PHP Type Juggling Pitfall

This repository demonstrates a common yet easily overlooked error in PHP: unexpected behavior arising from loose comparison (`==`) instead of strict comparison (`===`).

Loose comparison in PHP can lead to unexpected results when comparing values of different types due to type juggling. The `bug.php` file illustrates this problem. The `bugSolution.php` file shows how to resolve this issue with strict comparison.

## Bug Description
The code uses loose comparison (`==`) in a conditional statement, resulting in incorrect evaluation due to PHP's automatic type conversion.

## Solution
The solution involves replacing the loose comparison (`==`) with a strict comparison (`===`), which prevents type juggling and ensures accurate comparisons.