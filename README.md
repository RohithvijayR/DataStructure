Competitive Programming Problems - Solutions
This repository contains solutions to several competitive programming problems. The solutions are implemented in C.

Problem List
Increasing Subarrays
Count the number of subarrays that can be made monotonic increasing using at most 
𝑀
M operations.

Subinterval Division
Divide a segment on the x-axis such that all points in a subsegment are closest to the same point. Calculate the sum of lengths of subsegments for each point.

Minimize Max Diff
Given an array in non-decreasing order, remove 
𝐾
K elements such that the maximum difference between consecutive elements is minimized.

Pair Swap
Given an array, swap at most one pair of elements to obtain the smallest lexicographical array possible.

A Single One
Minimize the number of reversals needed to bring the single "1" to every position in the array, avoiding forbidden positions.

Platforms
Minimize the total cost of moving platforms to avoid having any balls fall strictly inside them.

Strings (Palindrome and Modifications)
Process queries to check if a substring is a palindrome and apply modifications like cutting, reversing, and inserting characters.

Word Ordering
Sort a list of strings using a custom lexicographical order defined by a given permutation of the alphabet.

Alphabet Rotation
Check if two words can be made equivalent by rotating the alphabet and determine if any word has an equivalent word in the set.

Pokemon Fight
Select Pokémon to fight such that all fights are won and maximize the sum of the remaining Pokémon’s combat power.

Path Travel
Given red and blue nodes in a linear graph, find the minimum distance from each red node to the nearest blue node.

Reconstruct Graph
Count the number of valid graphs with given distances from node 
1
1 to every other node, containing specified edges and ensuring connectivity.

No Prime Sum
Given a set of integers, remove the minimum number of elements such that no two elements left in the set sum to a prime number.

Solutions
Each problem has been solved using efficient algorithms with time complexity considerations to handle the problem’s constraints:

Sorting: Many solutions involve sorting the input arrays to improve efficiency.
Two-Pointer Approach: Used in problems like finding the closest red/blue nodes.
Greedy Approaches: Used in problems like minimizing the maximum difference in arrays.
Graph Theory: Used for problems related to graph reconstruction and edge removals.
Dynamic Programming/DFS: Applied in problems where subproblems need to be solved recursively.



**Setup and Compilation
To compile and run the programs:

Clone the repository:

git clone https://github.com/RohithvijayR/DataStructure.git

cd DataStructure

Compile the C programs:

gcc -o solution solution.c

Run the compiled program:

./solution


Replace solution with the specific problem solution file (e.g., increasing_subarrays.c).**
