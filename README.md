Two Sum – Problem & Solution

Problem:
Given an array of integers nums and an integer target, return the indices of the two numbers such that they add up to target.
Each input has exactly one solution, and the same element cannot be used twice.

Approach:
This solution uses a hash map to achieve optimal performance.

Iterate through the array once

For each number, calculate the complement needed to reach target

Check if the complement already exists in the hash map

If found, return the indices

Otherwise, store the current number and its index in the map

This avoids the need for nested loops and significantly improves efficiency.

Time Complexity: O(n)
Space Complexity: O(n)

Why this works:
The hash map allows constant-time lookups, making it possible to find the required pair in a single pass.
