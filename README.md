We are done for this year. We look forward to seeing you at Hacktoberfest 2026. Until then, HAPPY CODING!


# The Algorithm & Data Structure Hub 🚀

[![Hacktoberfest](https://img.shields.io/badge/Hacktoberfest-2025-orange?style=for-the-badge)](https://hacktoberfest.com/)

Welcome to **The Algorithm & Data Structure Hub**! This repository is a community-driven collection of common algorithms and data structures implemented in various programming languages. It's a resource for learning and a place for developers to make their first meaningful open-source contributions.

## 🌟 Project Goals
The mission of this repository is to become a high-quality, community-curated resource for learning fundamental algorithms and data structures. While we enthusiastically participate in events like Hacktoberfest, our primary goal is to create a lasting educational tool for developers of all skill levels. We are committed to maintaining a high standard of quality for all contributions.

## 🎃 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

This project was built to be a welcoming and organized space for developers to make their first meaningful open-source contributions. We have a detailed guide on how to get started, including our folder structure, coding standards, and the entire pull request workflow.

HEAD
👉 **To get started, please read our [Contributing Guidelines (CONTRIBUTING.md)](CONTRIBUTING.md)!**

**Pull requests that do not follow these guidelines will be marked as `invalid` and closed.**

### Required Folder Structure

Your contribution **MUST** follow this structure to be accepted.

```
/data_structures
    /LinkedList
        /python
            /singly_linked_list.py
        /javascript
            /SinglyLinkedList.js
/algorithms
    /sorting
        /bubble_sort
            /c_plus_plus
                /bubble_sort.cpp
```

### Repository Structure

The repository is organized to make it easy to explore algorithms and data structure implementations across multiple programming languages.

#### ALGORITHMS

```
algorithms
├── array
│   ├── dutch_national_flag
│   │   └── python
│   │       └── sort_colors.py
│   ├── majority_element
│   │   └── python
│   │       └── majority_element.py
│   ├── max_subarray
│   │   └── python
│   │       ├── kadane.py
│   │       └── test_kadane.py
│   ├── merge_sorted
│   │   └── javascript
│   │       └── MergeSorted.js
│   ├── missing_number
│   │   └── python
│   │       └── missing_number.py
│   ├── move_zeroes
│   │   └── python
│   │       └── move_zeroes.py
│   ├── pascals_triangle
│   │   └── python
│   │       └── pascals_triangle.py
│   ├── product_except_self
│   │   └── python
│   │       └── product.py
│   ├── rotate
│   │   └── python
│   │       └── rotate_array.py
│   ├── sliding_window_max
│   │   └── python
│   │       └── sliding_window.py
│   └── two_sum
│       └── python
│           ├── test_two_sum.py
│           └── two_sum.py
├── backtracking
│   ├── n_queens
│   │   └── python
│   │       └── n_queens.py
│   ├── permutations
│   │   └── javascript
│   │       └── Permutations.js
│   └── sudoku_solver
│       └── python
│           └── sudoku.py
├── bit_manipulation
│   ├── check_ith_bit
│   │   └── c
│   │       └── check_bit.c
│   ├── single_number
│   │   └── python
│   │       └── single_number.py
│   └── swap_numbers
│       └── java
│           └── SwapNumbers.java
├── dfs
│   └── python
│       └── dfs.py
├── dynamic_programming
│   ├── coin_change
│   │   └── javascript
│   │       ├── CoinChange.js
│   │       └── TestCoinChange.js
│   ├── longest_common_subsequence
│   │   └── python
│   │       └── lcs.py
│   ├── rod_cutting
│   │   └── c_plus_plus
│   │       └── rod_cutting.cpp
│   └── subset_sum
│       └── python
│           └── subset_sum.py
├── graph
│   ├── a_star
│   │   └── python
│   │       └── a_star.py
│   ├── bellman_ford
│   │   └── python
│   │       └── bellman_ford.py
│   ├── bfs
│   │   └── python
│   │       └── bfs.py
│   └── dijkstra
│       └── python
│           └── dijkstra.py
├── math
│   ├── factorial
│   │   ├── c_plus_plus
│   │   │   └── factorial.cpp
│   │   └── python
│   │       ├── factorial.py
│   │       └── test_factorial.py
│   ├── fibonacci
│   │   ├── javascript
│   │   │   └── FibonacciRecursive.js
│   │   └── python
│   │       └── fibonacci_iterative.py
│   ├── gcd
│   │   └── c_plus_plus
│   │       └── gcd.cpp
│   ├── integer_to_roman
│   │   └── java
│   │       └── IntegerToRoman.java
│   ├── power
│   │   └── python
│   │       └── power.py
│   └── README.md
├── puzzles
│   └── tower_of_hanoi
│       └── python
│           └── tower_of_hanoi.py
├── README.md
├── searching
│   ├── binary_search
│   │   └── python
│   │       └── binary_search_iterative.py
│   ├── jump_search
│   │   └── java
│   │       └── JumpSearch.java
│   └── linear_search
│       ├── java
│       │   └── LinearSearch.java
│       └── python
│           ├── linear_search.py
│           └── test_linear_search.py
├── sorting
│   ├── bubble_sort
│   │   ├── python
│   │   │   ├── bubble_sort.py
│   │   │   └── test_bubble_sort.py
│   │   └── rust
│   │       └── bubble_sort.rs
│   ├── counting_sort
│   │   └── python
│   │       └── counting_sort.py
│   ├── heap_sort
│   │   └── java
│   │       └── HeapSort.java
│   ├── insertion_sort
│   │   ├── java
│   │   │   └── InsertionSort.java
│   │   └── python
│   │       ├── insertion_sort.py
│   │       └── test_insertion_sort.py
│   ├── quick_sort
│   │   └── javascript
│   │       └── QuickSort.js
│   ├── radix_sort
│   │   └── c_plus_plus
│   │       └── radix_sort.cpp
│   └── selection_sort
│       └── python
│           └── selection_sort.py
├── string
│   ├── anagram
│   │   └── python
│   │       └── anagram.py
│   ├── first_non_repeating
│   │   └── java
│   │       └── FirstNonRepeating.java
│   ├── group_anagrams
│   │   └── python
│   │       └── group_anagrams.py
│   ├── longest_palindrome
│   │   └── python
│   │       └── longest_palindrome.py
│   ├── palindrome
│   │   └── python
│   │       └── palindrome.py
│   ├── README.md
│   ├── reverse
│   │   └── javascript
│   │       └── ReverseString.js
│   └── valid_parentheses
│       └── python
│           └── valid_parentheses.py
└── tree
    ├── invert
    │   └── python
    │       ├── invert_tree.py
    │       └── test_invert_tree.py
    ├── max_depth
    │   └── python
    │       └── max_depth.py
    └── traversal
        ├── java
        │   └── PostOrder.java
        └── python
            └── level_order.py

```
#### DATA STRUCTURES
```
data_structures
├── Deque
│   └── python
│       └── deque.py
├── FenwickTree
│   └── c_plus_plus
│       └── fenwick_tree.cpp
├── Graph
│   └── python
│       └── graph_adjacency_list.py
├── HashTable
│   └── javascript
│       └── HashTable.js
├── Heap
│   └── python
│       └── min_heap.py
├── LinkedList
│   ├── c_plus_plus
│   │   └── doubly_linked_list.cpp
│   ├── java
│   │   └── CircularLinkedList.java
│   └── python
│       ├── interactive_demo.py
│       └── singly_linked_list.py
├── Queue
│   └── python
│       └── queue_using_stack.py
├── README.md
├── Stack
│   ├── c
│   │   └── stack.c
│   ├── javascript
│   │   └── Stack.js
│   └── python
│       └── stack.py
└── Tree
    └── python
        └── avl_tree.py
```

## License

This project is licensed under the [MIT License](LICENSE).
