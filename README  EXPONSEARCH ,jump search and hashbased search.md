 Exponential Search
How It Works:
Starts by finding the range where the element might exist by doubling the index (1, 2, 4, 8, ...).

Once the range is found, it performs binary search within that range.

Works on sorted arrays.

Complexity:
Time: O(log i), where i is the index of the target

Space: O(1) (iterative), O(log i) (if binary search is recursive)
Jump Search
 How It Works:
Suitable for sorted arrays.

Jumps ahead by a fixed block size (√n) until it finds a block where the target might be.

Then does a linear search within that block.
Complexity:
Time: O(√n)

Space: O(1)
Hashbased search
how It Works:
Uses a hash table (e.g., unordered_map) for direct access to elements using their key.

Best for unsorted data where quick lookup is needed.

 Complexity:
Time:

Best/Average: O(1)

Worst: O(n) (if there are collisions)

Space: O(n)
