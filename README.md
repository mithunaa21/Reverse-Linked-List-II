# Reverse Linked List II

## Problem Statement
Given the head of a singly linked list and two integers `left` and `right` where `1 <= left <= right <= n`, reverse the nodes of the list from position `left` to `right`, and return the modified linked list.

## Example

### Example 1:
```plaintext
Input: head = [1,2,3,4,5], left = 2, right = 4
Output: [1,4,3,2,5]
```

### Example 2:
```plaintext
Input: head = [5], left = 1, right = 1
Output: [5]
```

## Constraints
- The number of nodes in the list is `n`.
- `1 <= n <= 500`
- `-500 <= Node.val <= 500`
- `1 <= left <= right <= n`

## Solution Approach
We solve this problem by:
1. Traversing the linked list to locate the `left` and `right` positions.
2. Storing values in an array for reversal.
3. Updating the linked list nodes with reversed values while maintaining the rest of the list unchanged.

## Implementation Approach
1. Traverse the list and store values from `left` to `right` in an array.
2. Reverse the stored values.
3. Assign the reversed values back to the respective nodes in the linked list.
4. Return the modified linked list.

## Usage
Pass the head of a linked list and two positions (`left` and `right`) to the function. The function will return the modified linked list with the specified section reversed.

## Contributing
Feel free to submit issues or pull requests if you have improvements!

