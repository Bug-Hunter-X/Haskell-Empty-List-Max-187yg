# Haskell Bug: Maximum of Empty List
This repository demonstrates a common runtime error in Haskell: attempting to find the maximum value of an empty list.  The `maximum` function requires at least one element; otherwise it throws an exception.

The `bug.hs` file contains the erroneous code. The `bugSolution.hs` file provides a corrected version that handles the case of an empty list gracefully.