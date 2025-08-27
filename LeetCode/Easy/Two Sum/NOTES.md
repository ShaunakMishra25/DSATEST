
          # Two Sum

          **Summary:** This algorithm utilizes a hash map (dictionary in Python) to efficiently find pairs of numbers that sum to a target value. It iterates through the input array 'nums', calculating the complement needed to reach the target for each number. If the complement is found in the hash map, it means a pair has been found, and their indices are returned. Otherwise, the current number and its index are added to the hash map for future checks.

          - Time Complexity: O(n) because the algorithm iterates through the input array 'nums' once. Hash map lookups and insertions have an average time complexity of O(1).
          - Space Complexity: O(n) because in the worst-case scenario, the hash map 'num_map' will store all the numbers from the input array 'nums'.
          