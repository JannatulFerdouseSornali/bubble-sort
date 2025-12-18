What is Bubble Sort?
Bubble Sort is the simplest sorting algorithm.
It repeatedly steps through the list, compares adjacent elements, and swaps them if they're in the wrong order.
The larger elements "bubble up" to the end of the list, like bubbles rising to the surface of water.

How It Works - Step by Step
Simple Example: Sort [5, 2, 8, 1, 9]
Pass 1: Compare and swap adjacent pairs from left to right
[5, 2, 8, 1, 9]
 ↓ ↓
[2, 5, 8, 1, 9]  (5 > 2, swap)
    ↓ ↓
[2, 5, 8, 1, 9]  (5 < 8, no swap)
       ↓ ↓
[2, 5, 1, 8, 9]  (8 > 1, swap)
          ↓ ↓
[2, 5, 1, 8, 9]  (8 < 9, no swap)

Result after Pass 1: [2, 5, 1, 8, 9]  ← 9 bubbled to end
