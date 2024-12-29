# Go Array Index Out of Bounds Error

This repository demonstrates a common error in Go: accessing an array index that is out of bounds.  Arrays in Go are zero-indexed, meaning the first element is at index 0, and the last element is at index len(array)-1.

The `bug.go` file contains code that attempts to access an index beyond the array's bounds, leading to a runtime panic.

The `bugSolution.go` file provides a corrected version of the code, demonstrating how to avoid this error. The fix involves carefully checking array boundaries before accessing elements.

This example highlights the importance of careful array index management in Go to prevent runtime errors.