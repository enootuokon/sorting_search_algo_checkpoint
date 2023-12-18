Iteration: The outer loop iterates over each element in the array, starting from the second element (index 1). The first element is considered to be already in the sorted sequence.

Current Element: Inside the loop, the current element (currentElement) is picked from the unsorted part of the array.

Comparison and Shifting: The inner loop (while loop) compares the current element with the elements in the sorted sequence (from j to 0) and shifts elements greater than the current element to the right.

Insertion: Once the correct position is found, the current element is inserted into its correct position in the sorted sequence.

Example Usage: The algorithm can be used by providing the array arr as input. After the algorithm completes, the array arr will be sorted in ascending order.
