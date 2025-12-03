Algorithms Project: Sorting Analysis & Restricted Tower of Hanoi

This project contains two main parts:

1. Sorting Algorithms Comparison
2. Restricted Tower of Hanoi (Recursive Algorithm)

Both tasks are implemented in C++, focusing on analyzing algorithm efficiency and recursive problem solving.

Task (1): Sorting Algorithms Comparison

Description:
This task compares the performance of three basic sorting algorithms:
- Bubble Sort
- Selection Sort
- Insertion Sort

Each algorithm is implemented in a function that returns the number of comparisons performed while sorting an array.


Task (2): Restricted Tower of Hanoi:

Problem Description:
This task implements a restricted version of the classical Tower of Hanoi puzzle using recursion.

In this version:
- You have 3 pegs: A, B, and C.
- You must move all disks from peg A to peg C.
- Every move must involve peg B meaning:
  - You can only place a disk on peg B, or
  - Move a disk from peg B.
- The usual rule still applies:
  - A larger disk cannot be placed on top of a smaller one**.

This restriction changes the classic solution, requiring more moves and a slightly different recursive approach.

Task(3): AVL tree Autocomplete:
This program implements an AVL tree to store a dictionary of words. An AVL tree is a self-balancing binary search tree where the balance factor (height of left subtree minus height of right subtree) of every node is maintained between -1 and 1. When a new word is inserted, the tree may perform rotations (left or right) to stay balanced. The program allows the user to type a prefix, then efficiently finds and displays all dictionary words that start with that prefix.


Task (4): Anagroms checker:
This C++ program checks if two words are anagrams. It sorts the letters of each word using bubble sort and then compares them. If the sorted words are the same, they are anagrams; otherwise, they are not.

Task(5): Alternating disks:
This C++ program sorts 2n disks (n dark D, n light L) from an alternating sequence (D L D L ...) to all light disks on the left and all dark disks on the right (L L ... D D).
It uses a modified bubble sort: swap any adjacent D and L where D is left of L. Each swap moves L left and D right. The program prints the initial and sorted sequences and the total number of moves.

Task(6): Fake coin:
This project solves the classic fake-coin problem using two different approaches. The first code implements an O(1) algorithm for exactly three coins, where only one or two fixed comparisons are needed to determine whether the fake coin is heavier or lighter. The second code extends the idea to n coins, where all genuine coins have weight 7, one random coin is modified (heavier or lighter), and the program scans the list to find the fake coin by checking which value differs from 7. While the first solution is constant-time, the second is O(n) because it must inspect each coin. Together, the two programs demonstrate the difference between constant-time logic for a fixed-size problem and linear-time scanning for a general case.
