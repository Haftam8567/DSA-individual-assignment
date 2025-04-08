 Ternary Search
Ternary search is similar to binary search, but instead of dividing the array into 2 parts, it divides it into 3 parts.

How it works:

It finds two midpoints: mid1 and mid2.

It compares the target with the values at both midpoints.

Based on the result, it eliminates one-third of the array each time

Time Complexity:

Best case: O(1) (if the element is found immediately)

Worst and Average case: O(log₃ n), which is similar to binary search (O(log₂ n)) but slightly slower in practice.

Space Complexity:

O(1) for iterative version, O(log n) for recursive.

 Interpolation Search
Interpolation search is an improved variant of binary search for uniformly distributed sorted arrays.

How it works:

Instead of splitting the array in the middle, it estimates where the target might be based on its value, using a formula:
pos = low + ((target - arr[low]) * (high - low)) / (arr[high] - arr[low])
This tries to "guess" the target's position like a human might when looking through a phonebook.

Time Complexity:

Best case: O(1)

Average case: O(log log n) — faster than binary search in the right conditions!

Worst case: O(n) — if data is not uniform or badly distributed.

Space Complexity:

O(1)
Ternary Search:
Splits the array into three parts. Works well for sorted data and especially for optimization problems.
 Time: O(log n)
 Space: O(log n) (recursive)

Interpolation Search:
Estimates the position based on value — like guessing where a name might be in a phonebook.
Works best on sorted, uniformly distributed arrays.
 Time: O(log log n) (best case)
Space: O(1)

