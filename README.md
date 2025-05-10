# Next-Permutation-


🎯 Problem Statement
Given an array of integers, rearrange numbers into the lexicographically next greater permutation. If not possible, return the smallest permutation.

**Example:**
```python
Input: [1,2,3] → Output: [1,3,2]
Input: [3,2,1] → Output: [1,2,3]
🚀 Solution Approach
Optimal 3-Step Algorithm:
Find Pivot: Traverse backward to find first decreasing element

Find Swap: Find smallest larger element than pivot

Reverse Suffix: Convert remaining elements to ascending order

Key Features:
Time Complexity: O(n) - Single pass through array

Space Complexity: O(1) - In-place modification

Edge Cases: Handles descending order arrays gracefully
