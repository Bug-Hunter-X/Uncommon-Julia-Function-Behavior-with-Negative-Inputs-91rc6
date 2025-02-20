# Uncommon Julia Function Behavior with Negative Inputs

This repository demonstrates a subtle bug in a seemingly simple Julia function that exhibits unexpected behavior when handling negative inputs.  The function intends to square positive inputs and return the absolute value of negative inputs. However, a misunderstanding of operator precedence or a lack of explicit type handling can lead to errors.

The `bug.jl` file contains the erroneous code. The `bugSolution.jl` file provides a corrected version.

This example highlights the importance of careful consideration of operator precedence and potential type-related issues in Julia, especially when dealing with functions involving both positive and negative numbers.
