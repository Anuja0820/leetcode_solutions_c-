unordered_map<int, int> seen; keeps track of the numbers and their indices.
For each number, check if the complement (target - nums[i]) exists in the map.
If it does → return the pair of indices.
If not → store the number and its index.
If no pair found → return {} (an empty vector)
