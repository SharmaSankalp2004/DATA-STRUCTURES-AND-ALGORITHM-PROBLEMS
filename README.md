# Swap Nodes in Pairs

**Problem:** Swap every two adjacent nodes in a singly linked list.

## Approach
- Create a dummy node to simplify swapping the first pair.
- Use `prev` to track the node before the current pair.
- Swap adjacent nodes by updating their `next` pointers.
- Move to the next pair and repeat until fewer than two nodes remain.

## Example
**Input:** `1 → 2 → 3 → 4`

**Output:** `2 → 1 → 4 → 3`

## Complexity Analysis
- **Time Complexity:** O(n)
- **Space Complexity:** O(1)

## Key Learning
Practiced pointer manipulation and swapping linked-list nodes without changing their values.
