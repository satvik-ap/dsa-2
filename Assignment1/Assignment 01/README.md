# Programming Assignment 1 -- Two-Pointer Technique
## Overview

This assignment demonstrates the Two-Pointer Technique using two
sorted-array problems. Each problem has a brute-force solution and an
optimized solution.

## Problems

### 1. Remove Duplicates from a Sorted Array

Remove repeated values in place and return the number of unique
elements.

**Input**

``` text
[1, 1, 2, 2, 3, 4, 4]
```

**Output**

``` text
[1, 2, 3, 4]
Unique count: 4
```

### 2. Pair Sum in a Sorted Array

Find two different elements whose sum equals the target.

**Input**

``` text
Array:  [1, 2, 4, 7, 11, 15]
Target: 15
```

**Output**

``` text
4 + 11 = 15
Indices: 2 and 4
```

## Approaches

-   **Brute Force:** Checks values or pairs directly.
-   **Two Pointers:** Uses two indexes and sorted order to solve the
    problem faster.

## Languages

-   C++ (C++17)
-   Java
-   Python

## Source Files

  File                Description
  ------------------- ----------------------------------------------
  `assignment.cpp`    C++ implementation of all four algorithms
  `Assignment.java`   Java implementation of all four algorithms
  `assignment.py`     Python implementation of all four algorithms

## Complexity

  Algorithm                              Time   Space
  ----------------------------------- ------- -------
  Brute Force -- Remove Duplicates      O(n²)    O(n)
  Two Pointers -- Remove Duplicates      O(n)    O(1)
  Brute Force -- Pair Sum               O(n²)    O(1)
  Two Pointers -- Pair Sum               O(n)    O(1)

## Execution Screenshots

Create a `screenshots` folder and add your actual screenshots with these
filenames.

### 1. C++ Output

<img width="1354" height="1161" alt="image" src="https://github.com/user-attachments/assets/32c03bd6-017d-4a9f-9a52-b7ac4e435d7a" />


### 2. Java Output

<img width="1508" height="1043" alt="image" src="https://github.com/user-attachments/assets/87eba72b-8172-4d7c-b0b1-9f75073af579" />


### 3. Python Output

<img width="1670" height="942" alt="image" src="https://github.com/user-attachments/assets/e29f3743-a763-424b-b304-1fa9dc73209d" />

## Conclusion

The Two-Pointer Technique reduces unnecessary comparisons and gives
linear-time solutions for both sorted-array problems.

## References

-   [C++ Reference](https://en.cppreference.com/w/)
-   [Java Documentation](https://docs.oracle.com/en/java/)
-   [Python Documentation](https://docs.python.org/3/)
-   [GeeksforGeeks -- Two
    Pointers](https://www.geeksforgeeks.org/two-pointers-technique/)
-   [LeetCode -- Remove
    Duplicates](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)
-   [LeetCode -- Two Sum
    II](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)
