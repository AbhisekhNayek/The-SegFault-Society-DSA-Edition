# **📌 Cracking the DSA Coding Interviews**  
🚀 *A complete guide to mastering DSA for coding interviews*  

## **📖 Introduction**  
👋 Hi, I'm **Abhisekh Nayek!**  

I come from a farmer's family, and I’ve always been passionate about technology. Despite my background, I worked my way up to becoming a **Software Engineer at Jobcode**. My journey has been full of challenges, but through **consistency, problem-solving, and a love for coding**, I’ve managed to grow my skills and help others do the same.  

This repository is my way of **giving back**—helping fellow programmers crack **DSA rounds** with a **structured and practical** approach.  

---

## **🗂️ Repository Overview**  
🔹 Categorized list of **DSA problems** with solutions  
🔹 **Brute Force → Better → Optimal** approaches for each problem  
🔹 **"Do’s and Don’ts"** for coding interviews  
🔹 **What to do when you're stuck** in a problem  
🔹 **Essential Coding Interview Patterns** to recognize problem-solving techniques  

---

## **📌 Golden Rules for Coding Interviews**  
### ✅ **Do’s**  
✔ Stay **Positive & Confident**  
✔ **Ask Clarifying Questions** before jumping in  
✔ **Think Aloud & Collaborate** during the interview  
✔ Start with a **Brute Force** approach, then optimize  
✔ **Admit when you don’t know something** and think logically  

### ❌ **Don’ts**  
✖ **Don’t jump straight to code**—plan first!  
✖ **Don’t assume**—always ask!  
✖ Avoid **jargon** without explanation  
✖ Never **skip communication**—explain your thought process  
✖ **Don’t be defensive about feedback**—learn and adapt  

---

## **💡 What to Do When Stuck?**  
🔹 Explain where you're stuck to the interviewer  
🔹 Break the problem into **smaller** steps  
🔹 Identify known **patterns** (Sliding Window, Two Pointers, etc.)  
🔹 Ask for hints if needed—interviews are **interactive!**  

---

## **🔥 DSA Problems by Category**  
Each category includes:  
- 📌 **Problem Statement**  
- ✅ **Brute Force Approach**  
- 🔥 **Better Approach**  
- ⚡ **Optimal Approach**  

## **📂 Topics Covered**
1. **Arrays**
2. **Strings**
3. **Sorting**
4. **Searching**
5. **Matrix**
6. **Hashing**
7. **Two Pointers**
8. **Prefix Sum**
9. **Recursion & Backtracking**
10. **Linked List**
11. **Stack**
12. **Queue**
13. **Dynamic Programming (DP)**
14. **Greedy Algorithms**
15. **Bit Manipulation**
16. **Trees**
17. **Graphs**
18. **Heap**
19. **Tries**
20. **Fenwick Tree**

---

## **📂 1. Arrays** 
---

<details>
  <summary>1️⃣ Second Largest Element in an Array (Easy)</summary>  

**🔹 Brute Force Approach**  
- Sort the array in descending order and return the second element.  
- **Time Complexity:** `O(N log N)`  
- **Space Complexity:** `O(1)`

**🔹 Better Approach**  
- Traverse twice:  
  - First to find the max element  
  - Second to find the second max  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach**  
- Traverse once, tracking `maxElement` and `secondMax`.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`  

</details>  



<details>
  <summary>2️⃣ Reverse an Array (Easy)</summary>  

**🔹 Brute Force Approach**  
- Use an extra array to copy elements in reverse order.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

**🔹 Optimal Approach (Two Pointers)**  
- Swap elements from start & end until they meet.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`  

</details>  



<details>
  <summary>3️⃣ Move All Zeros to End (Easy)</summary>  

**🔹 Brute Force Approach**  
- Create a new array, add non-zero elements first, then zeros.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

**🔹 Optimal Approach (Two Pointers)**  
- One pointer tracks **non-zero positions**, another iterates.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`  

</details>  



<details>
  <summary>4️⃣ Buy & Sell Stock (Single Transaction) (Easy)</summary>  

**🔹 Brute Force Approach**  
- Try all possible `(buy, sell)` pairs and get max profit.  
- **Time Complexity:** `O(N²)`

**🔹 Optimal Approach**  
- Track **minimum price so far** and **max profit** in one pass.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  



<details>
  <summary>5️⃣ Rotate an Array (Medium)</summary>  

**🔹 Brute Force Approach**  
- Use an extra array and shift elements.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

**🔹 Optimal Approach (Reverse Method)**  
1. Reverse the whole array.  
2. Reverse the first `k` elements.  
3. Reverse the rest of the array.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  



<details>
  <summary>6️⃣ Majority Element (Medium)</summary>  

**🔹 Brute Force Approach**  
- Count frequency of each element.  
- **Time Complexity:** `O(N²)`, **Space Complexity:** `O(1)`

**🔹 Better Approach**  
- Use a HashMap.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

**🔹 Optimal Approach (Boyer-Moore Voting Algorithm)**  
- Track **potential majority element** and its count.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  



<details>
  <summary>7️⃣ Kadane's Algorithm – Maximum Subarray Sum (Medium)</summary>  

**🔹 Brute Force Approach**  
- Compute sum for all subarrays.  
- **Time Complexity:** `O(N²)`

**🔹 Optimal Approach (Kadane’s Algorithm)**  
- Track `currentSum` and `maxSum`.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  



<details>
  <summary>8️⃣ Maximum Product Subarray (Medium)</summary>  

**🔹 Brute Force Approach**  
- Compute product of all subarrays.  
- **Time Complexity:** `O(N²)`

**🔹 Optimal Approach**  
- Track `maxProduct` and `minProduct` dynamically.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  



<details>
  <summary>9️⃣ Longest Consecutive Sequence (Hard)</summary>  

**🔹 Brute Force Approach**  
- Sort and traverse to count streaks.  
- **Time Complexity:** `O(N log N)`

**🔹 Optimal Approach (Using Set)**  
- Use a HashSet for fast lookup.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

</details>  



<details>
  <summary>🔟 Subarray Sum Equals K (Medium)</summary>  

**🔹 Brute Force Approach**  
- Try all subarrays and check sum.  
- **Time Complexity:** `O(N²)`

**🔹 Optimal Approach (Prefix Sum + HashMap)**  
- Store cumulative sums and check for `(currentSum - k)`.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

</details>  

---

## **📂 2. Strings**  
---
<details>
  <summary>1️⃣ Anagram (Easy)</summary>  

**🔹 Brute Force Approach**  
- Sort both strings and compare.  
- **Time Complexity:** `O(N log N)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (HashMap / Frequency Array)**  
- Count character frequencies and compare.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>2️⃣ Non-Repeating Character (Easy)</summary>  

**🔹 Brute Force Approach**  
- Check each character’s occurrence in the string.  
- **Time Complexity:** `O(N²)`

**🔹 Optimal Approach (HashMap / Frequency Array)**  
- Use a frequency array to track character occurrences.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>3️⃣ String Rotation of Each Other (Easy)</summary>  

**🔹 Brute Force Approach**  
- Generate all rotations and compare.  
- **Time Complexity:** `O(N²)`

**🔹 Optimal Approach (Concatenation Trick)**  
- Check if `s1` is a substring of `s2 + s2`.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

</details>  

<details>
  <summary>4️⃣ Reverse a String (Easy)</summary>  

**🔹 Two-Pointer Approach**  
- Swap characters from start to end.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>5️⃣ Palindrome Check (Medium)</summary>  

**🔹 Brute Force Approach**  
- Reverse and compare.  
- **Time Complexity:** `O(N)`

**🔹 Optimal Approach (Two Pointers)**  
- Compare characters from both ends.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>6️⃣ Add Two Binary Strings (Medium)</summary>  

**🔹 Brute Force Approach**  
- Convert to decimal, add, and convert back.  
- **Time Complexity:** `O(N)`

**🔹 Optimal Approach (Bit Manipulation)**  
- Traverse from right, sum bits, and carry forward.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>7️⃣ Implement ATOI (Medium)</summary>  

**🔹 Steps to Implement:**  
1. Ignore leading whitespaces.  
2. Handle `+` / `-` sign.  
3. Convert valid digits.  
4. Handle integer overflow.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>8️⃣ Remove All Occurrences of a Substring (Medium)</summary>  

**🔹 Brute Force Approach**  
- Replace occurrences iteratively.  
- **Time Complexity:** `O(N²)`

**🔹 Optimal Approach (KMP Algorithm)**  
- Use KMP for efficient substring search.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

</details>  

<details>
  <summary>9️⃣ Reverse Words in a String (Medium)</summary>  

**🔹 Brute Force Approach**  
- Split, reverse, and join.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

**🔹 Optimal Approach (In-Place Reversal)**  
- Reverse entire string, then words.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>🔟 String Compression (Medium)</summary>  

**🔹 Brute Force Approach**  
- Count characters manually.  
- **Time Complexity:** `O(N²)`

**🔹 Optimal Approach (Two Pointers)**  
- Use a result string and track counts.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

</details>  

<details>
  <summary>1️⃣1️⃣ KMP Pattern Matching (Hard)</summary>  

**🔹 Approach (Prefix Function + KMP Algorithm)**  
- Precompute prefix function for pattern.  
- **Time Complexity:** `O(N + M)`, **Space Complexity:** `O(M)`

</details>  

<details>
  <summary>1️⃣2️⃣ Min Chars to Add for Palindrome (Hard)</summary>  

**🔹 Optimal Approach (KMP + Reverse String)**  
- Append reverse and compute LPS array.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

</details>  

<details>
  <summary>1️⃣3️⃣ Permutation in String (Hard)</summary>  

**🔹 Brute Force Approach**  
- Generate all permutations and check.  
- **Time Complexity:** `O(N!)`

**🔹 Optimal Approach (Sliding Window + Frequency Array)**  
- Use character frequency comparison within a sliding window.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  

---
## **📂 3. Sorting**
---


<details>
  <summary>1️⃣ Bubble Sort (Easy)</summary>  

**🔹 Brute Force Approach**  
- Repeatedly swap adjacent elements if they are in the wrong order.  
- **Time Complexity:** `O(N^2)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach**  
- Optimized by detecting early sorted arrays.  
- **Time Complexity:** `O(N^2)` (Worst), `O(N)` (Best if already sorted), **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>2️⃣ Selection Sort (Easy)</summary>  

**🔹 Approach**  
- Find the minimum element and swap it with the current index.  
- **Time Complexity:** `O(N^2)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>3️⃣ Insertion Sort (Easy)</summary>  

**🔹 Approach**  
- Build a sorted array one element at a time by inserting elements at the correct position.  
- **Time Complexity:** `O(N^2)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>4️⃣ Quick Sort (Easy)</summary>  

**🔹 Approach (Divide & Conquer)**  
- Pick a pivot, partition the array, and sort recursively.  
- **Time Complexity:** `O(N log N)` (Average), `O(N^2)` (Worst in unbalanced partitioning), **Space Complexity:** `O(log N)`

</details>  

<details>
  <summary>5️⃣ Sort 0’s, 1’s, and 2’s (Medium)</summary>  

**🔹 Brute Force Approach**  
- Sort the array normally (like merge/quick sort).  
- **Time Complexity:** `O(N log N)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Dutch National Flag Algorithm)**  
- Use three pointers (low, mid, high) to place elements in correct positions.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>6️⃣ Find H-Index of a Research Paper (Medium)</summary>  

**🔹 Brute Force Approach**  
- Sort citations and check conditions manually.  
- **Time Complexity:** `O(N log N)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Counting Sort / Bucket Sort)**  
- Use frequency counting to determine H-Index efficiently.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

</details>  

<details>
  <summary>7️⃣ Count Inversion (Medium)</summary>  

**🔹 Brute Force Approach**  
- Count pairs `(i, j)` where `i < j` and `arr[i] > arr[j]`.  
- **Time Complexity:** `O(N^2)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Merge Sort Modification)**  
- Modify merge sort to count inversions while merging.  
- **Time Complexity:** `O(N log N)`, **Space Complexity:** `O(N)`

</details>  

<details>
  <summary>8️⃣ Merge Overlapping Intervals (Medium)</summary>  

**🔹 Brute Force Approach**  
- Compare all intervals and merge manually.  
- **Time Complexity:** `O(N^2)`, **Space Complexity:** `O(N)`

**🔹 Optimal Approach (Sorting + Merging)**  
- Sort intervals, then iterate and merge overlapping ones.  
- **Time Complexity:** `O(N log N)`, **Space Complexity:** `O(N)`

</details>  

<details>
  <summary>9️⃣ Insert New Intervals (Medium)</summary>  

**🔹 Approach**  
- Find correct insertion position and merge accordingly.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

</details>  

<details>
  <summary>🔟 Non-Overlapping Intervals (Medium)</summary>  

**🔹 Approach (Greedy Algorithm)**  
- Sort by end time, then greedily remove intervals causing overlap.  
- **Time Complexity:** `O(N log N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>1️⃣1️⃣ Merge Without Extra Space (Medium)</summary>  

**🔹 Brute Force Approach**  
- Merge and sort the entire combined array.  
- **Time Complexity:** `O((N+M) log (N+M))`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Gap Method)**  
- Use a shrinking gap to rearrange elements in place.  
- **Time Complexity:** `O(N log N)`, **Space Complexity:** `O(1)`

</details>  

---

## **📂 4. Searching** 
---

<details>
  <summary>1️⃣ Find Peak Element (Easy)</summary>  

**🔹 Brute Force Approach**  
- Traverse the array and check neighbors.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Binary Search)**  
- Apply binary search to find the peak efficiently.  
- **Time Complexity:** `O(log N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>2️⃣ Number of Occurrences (Easy)</summary>  

**🔹 Brute Force Approach**  
- Traverse and count occurrences manually.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Binary Search)**  
- Find the first and last occurrence using binary search.  
- **Time Complexity:** `O(log N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>3️⃣ Sorted and Rotated Minimum (Easy)</summary>  

**🔹 Brute Force Approach**  
- Traverse the array to find the minimum element.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Binary Search)**  
- Use binary search to locate the pivot (minimum element).  
- **Time Complexity:** `O(log N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>4️⃣ Search in Rotated Sorted Array (Medium)</summary>  

**🔹 Brute Force Approach**  
- Perform linear search.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

**🔹 Better Approach (Binary Search with Extra Checks)**  
- First, find the rotation point, then apply binary search.  
- **Time Complexity:** `O(log N)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Modified Binary Search)**  
- Identify the sorted half and perform binary search in the correct part.  
- **Time Complexity:** `O(log N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>5️⃣ K-th Element of Two Arrays (Medium)</summary>  

**🔹 Brute Force Approach**  
- Merge both arrays and return the k-th element.  
- **Time Complexity:** `O(N + M)`, **Space Complexity:** `O(N + M)`

**🔹 Better Approach (Two-Pointer Merge)**  
- Merge up to the k-th element without full merging.  
- **Time Complexity:** `O(K)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Binary Search on Smaller Array)**  
- Partition the two arrays to find the k-th element efficiently.  
- **Time Complexity:** `O(log min(N, M))`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>6️⃣ K-th Missing Positive Number in a Sorted Array (Medium)</summary>  

**🔹 Brute Force Approach**  
- Traverse and count missing numbers manually.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Binary Search)**  
- Use binary search to directly locate the k-th missing number.  
- **Time Complexity:** `O(log N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>7️⃣ Allocate Minimum Pages (Medium)</summary>  

**🔹 Brute Force Approach**  
- Try all possible distributions.  
- **Time Complexity:** `O(2^N)`, **Space Complexity:** `O(1)`

**🔹 Better Approach (Prefix Sum + Recursion)**  
- Use recursion with memoization.  
- **Time Complexity:** `O(N^2)`, **Space Complexity:** `O(N)`

**🔹 Optimal Approach (Binary Search on Answer)**  
- Apply binary search on the max pages allocated.  
- **Time Complexity:** `O(N log N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>8️⃣ Aggressive Cows (Medium)</summary>  

**🔹 Brute Force Approach**  
- Try placing cows at every possible distance.  
- **Time Complexity:** `O(N^2)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Binary Search on Minimum Distance)**  
- Use binary search to maximize the minimum distance.  
- **Time Complexity:** `O(N log N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>9️⃣ Painters Partition (Medium)</summary>  

**🔹 Brute Force Approach**  
- Generate all possible partitions and find the one with the least max time.  
- **Time Complexity:** `O(2^N)`, **Space Complexity:** `O(1)`

**🔹 Better Approach (Dynamic Programming)**  
- Use DP to store results of previous partitions.  
- **Time Complexity:** `O(N^2)`, **Space Complexity:** `O(N)`

**🔹 Optimal Approach (Binary Search on Answer)**  
- Use binary search to find the minimum maximum time required.  
- **Time Complexity:** `O(N log N)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>🔟 Median of Two Sorted Arrays (Hard)</summary>  

**🔹 Brute Force Approach**  
- Merge both arrays and find the median.  
- **Time Complexity:** `O(N + M)`, **Space Complexity:** `O(N + M)`

**🔹 Better Approach (Two Pointers)**  
- Merge until the median is found without storing extra space.  
- **Time Complexity:** `O((N + M) / 2)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Binary Search on Smaller Array)**  
- Use binary search to partition both arrays correctly.  
- **Time Complexity:** `O(log min(N, M))`, **Space Complexity:** `O(1)`

</details>  

---

## **📂 5. Matrix** 
--- 

<details>
  <summary>1️⃣ Search in a Row-Wise Sorted Matrix (Medium)</summary>  

**🔹 Brute Force Approach**  
- Perform a linear search on all elements.  
- **Time Complexity:** `O(N*M)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Binary Search in Each Row)**  
- Apply binary search in each row separately.  
- **Time Complexity:** `O(N log M)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>2️⃣ Search in a Row-Column Sorted Matrix (Medium)</summary>  

**🔹 Brute Force Approach**  
- Scan the entire matrix for the target.  
- **Time Complexity:** `O(N*M)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Start from Top-Right or Bottom-Left)**  
- Move left if the current element is larger, move down if smaller.  
- **Time Complexity:** `O(N + M)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>3️⃣ Rotate Matrix by 90 Degrees (Medium)</summary>  

**🔹 Brute Force Approach**  
- Create a new matrix and map elements accordingly.  
- **Time Complexity:** `O(N*M)`, **Space Complexity:** `O(N*M)`

**🔹 Optimal Approach (Transpose + Reverse Rows)**  
- First, transpose the matrix, then reverse each row.  
- **Time Complexity:** `O(N*M)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>4️⃣ Search in a Sorted Matrix (Medium)</summary>  

**🔹 Brute Force Approach**  
- Perform a simple linear search.  
- **Time Complexity:** `O(N*M)`, **Space Complexity:** `O(1)`

**🔹 Better Approach (Binary Search in 1D View)**  
- Treat the matrix as a 1D sorted array and apply binary search.  
- **Time Complexity:** `O(log(N*M))`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>5️⃣ Set Matrix Zeroes (Medium)</summary>  

**🔹 Brute Force Approach**  
- Create a copy of the matrix and update it based on zero positions.  
- **Time Complexity:** `O(N*M)`, **Space Complexity:** `O(N*M)`

**🔹 Better Approach (Row and Column Hashing)**  
- Use separate arrays to mark which rows/columns should be zero.  
- **Time Complexity:** `O(N*M)`, **Space Complexity:** `O(N+M)`

**🔹 Optimal Approach (Modify Matrix in Place)**  
- Use the first row and first column as markers.  
- **Time Complexity:** `O(N*M)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>6️⃣ Print Spiral Matrix (Hard)</summary>  

**🔹 Brute Force Approach**  
- Use multiple loops to simulate the spiral traversal.  
- **Time Complexity:** `O(N*M)`, **Space Complexity:** `O(N*M)` (if storing the result)

**🔹 Optimal Approach (Layer-wise Traversal)**  
- Maintain boundaries (top, bottom, left, right) and traverse layer by layer.  
- **Time Complexity:** `O(N*M)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>7️⃣ Find the Median in a Row-Wise Sorted Matrix (Hard)</summary>  

**🔹 Brute Force Approach**  
- Flatten the matrix and sort it to find the median.  
- **Time Complexity:** `O(N*M log(N*M))`, **Space Complexity:** `O(N*M)`

**🔹 Optimal Approach (Binary Search on Median Value)**  
- Use binary search on the value range to determine the median position.  
- **Time Complexity:** `O(N log Max-Min)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>8️⃣ Kth Smallest Element in a Sorted Matrix (Medium)</summary>  

**🔹 Brute Force Approach**  
- Flatten and sort the matrix, then return the k-th smallest element.  
- **Time Complexity:** `O(N*M log(N*M))`, **Space Complexity:** `O(N*M)`

**🔹 Optimal Approach (Min Heap / Binary Search)**  
- Use a min heap or binary search on values to efficiently find the k-th smallest.  
- **Time Complexity:** `O(K log N)`, **Space Complexity:** `O(N)`

</details>  

<details>
  <summary>9️⃣ Boolean Matrix Problem (Medium)</summary>  

**🔹 Brute Force Approach**  
- Use an extra matrix to track changes and update the original.  
- **Time Complexity:** `O(N*M)`, **Space Complexity:** `O(N*M)`

**🔹 Optimal Approach (Row and Column Markers)**  
- Use the first row and column as flags for modification.  
- **Time Complexity:** `O(N*M)`, **Space Complexity:** `O(1)`

</details>  

<details>
  <summary>🔟 Maximum Rectangle of 1s in a Binary Matrix (Hard)</summary>  

**🔹 Brute Force Approach**  
- Check all possible submatrices to find the largest rectangle of 1s.  
- **Time Complexity:** `O(N^3)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Histogram + Stack)**  
- Treat each row as a histogram and apply the **Largest Rectangle in Histogram** approach.  
- **Time Complexity:** `O(N*M)`, **Space Complexity:** `O(M)`

</details>  

Here's how your **Hashing** section will look in your GitHub repository:  

---

## **📂 6. Hashing**  
---  

<details>  
  <summary>1️⃣ Two Sum - Pair with Given Sum (Easy)</summary>  

**🔹 Brute Force Approach**  
- Iterate through all pairs and check if their sum equals the target.  
- **Time Complexity:** `O(N²)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Using HashMap)**  
- Use a HashMap to store visited elements and find the complement in `O(1)`.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

</details>  

<details>  
  <summary>2️⃣ Three Sum (Easy)</summary>  

**🔹 Brute Force Approach**  
- Check all triplets and see if their sum equals zero.  
- **Time Complexity:** `O(N³)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Sorting + Two Pointers)**  
- Sort the array and use two pointers to find pairs.  
- **Time Complexity:** `O(N²)`, **Space Complexity:** `O(1)`

</details>  

<details>  
  <summary>3️⃣ Four Sum (Easy)</summary>  

**🔹 Brute Force Approach**  
- Iterate through all quadruplets and check for the target sum.  
- **Time Complexity:** `O(N⁴)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Sorting + Two Pointers)**  
- Sort the array, fix two elements, and use two pointers to find remaining pairs.  
- **Time Complexity:** `O(N³)`, **Space Complexity:** `O(1)`

</details>  

<details>  
  <summary>4️⃣ Find Missing & Repeating Value (Easy)</summary>  

**🔹 Brute Force Approach**  
- Count occurrences using two loops.  
- **Time Complexity:** `O(N²)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Using HashMap / Math Formula)**  
- Use frequency hash map OR solve using sum and sum of squares formula.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N) / O(1)`

</details>  

<details>  
  <summary>5️⃣ Union of Arrays with Duplicates (Easy)</summary>  

**🔹 Brute Force Approach**  
- Merge both arrays and remove duplicates manually.  
- **Time Complexity:** `O(N+M)`, **Space Complexity:** `O(N+M)`

**🔹 Optimal Approach (Using HashSet)**  
- Store elements in a HashSet to remove duplicates efficiently.  
- **Time Complexity:** `O(N+M)`, **Space Complexity:** `O(N+M)`

</details>  

<details>  
  <summary>6️⃣ Intersection of Two Arrays with Duplicate Elements (Easy)</summary>  

**🔹 Brute Force Approach**  
- Iterate through both arrays and find common elements manually.  
- **Time Complexity:** `O(N*M)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Using HashMap)**  
- Use a HashMap to store frequencies and find common elements.  
- **Time Complexity:** `O(N+M)`, **Space Complexity:** `O(N)`

</details>  

<details>  
  <summary>7️⃣ Find All Triplets with Zero Sum (Medium)</summary>  

**🔹 Brute Force Approach**  
- Use three nested loops to find all triplets summing to zero.  
- **Time Complexity:** `O(N³)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Sorting + Two Pointers)**  
- Sort the array and use two pointers for each fixed element.  
- **Time Complexity:** `O(N²)`, **Space Complexity:** `O(1)`

</details>  

<details>  
  <summary>8️⃣ Longest Consecutive Subsequence (Medium)</summary>  

**🔹 Brute Force Approach**  
- Sort the array and find longest consecutive sequence.  
- **Time Complexity:** `O(N log N)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Using HashSet)**  
- Store elements in a HashSet and check for sequence starts.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

</details>  

<details>  
  <summary>9️⃣ Subarrays with Sum K (Medium)</summary>  

**🔹 Brute Force Approach**  
- Generate all subarrays and check their sum.  
- **Time Complexity:** `O(N²)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Using Prefix Sum + HashMap)**  
- Maintain a prefix sum and count occurrences of `(prefix_sum - k)`.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

</details>  

<details>  
  <summary>🔟 Count Subarrays with Given XOR (Medium)</summary>  

**🔹 Brute Force Approach**  
- Generate all subarrays and compute XOR values.  
- **Time Complexity:** `O(N²)`, **Space Complexity:** `O(1)`

**🔹 Optimal Approach (Using HashMap - Prefix XOR)**  
- Store prefix XOR counts in a HashMap and find `(prefix_XOR ^ target)`.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

</details>  

---

## **📂 7. Two Pointer**  
---  

<details> <summary>1️⃣ Count Pairs Whose Sum Is Less Than Target (Easy)</summary> 🔹 **Brute Force Approach**
Iterate through all pairs and check if their sum is less than the target.

Time Complexity: O(N²), Space Complexity: O(1)

🔹 Optimal Approach (Two Pointer Technique)

Sort the array. Use two pointers—one at the beginning and one at the end. If the sum is less than the target, count all pairs from left to right pointer and move left pointer forward. Otherwise, move the right pointer backward.

Time Complexity: O(N log N + N) ≈ O(N log N), Space Complexity: O(1)

</details> <details> <summary>2️⃣ Pair With Given Sum in a Sorted Array (Easy)</summary>
🔹 Brute Force Approach

Iterate through all pairs and check if their sum equals the given sum.

Time Complexity: O(N²), Space Complexity: O(1)

🔹 Optimal Approach (Two Pointer Technique)

Use two pointers—one at the start and one at the end. If their sum matches the target, return the indices. If the sum is too small, move the left pointer forward; if too large, move the right pointer backward.

Time Complexity: O(N), Space Complexity: O(1)

</details> <details> <summary>3️⃣ Sum Pair Closest to Target (Easy)</summary>
🔹 Brute Force Approach

Iterate through all pairs and track the closest sum to the target.

Time Complexity: O(N²), Space Complexity: O(1)

🔹 Optimal Approach (Two Pointer Technique)

Sort the array and use two pointers—one at the start and one at the end. Update the closest sum based on comparison with the target.

Time Complexity: O(N log N + N) ≈ O(N log N), Space Complexity: O(1)

</details> <details> <summary>4️⃣ Indexes of Subarray Sum (Medium)</summary>
🔹 Brute Force Approach

Check all subarrays and find the one with the given sum.

Time Complexity: O(N²), Space Complexity: O(1)

🔹 Optimal Approach (Two Pointer Technique / Sliding Window)

Use a sliding window approach to adjust the sum dynamically by moving left and right pointers.

Time Complexity: O(N), Space Complexity: O(1)

</details> <details> <summary>5️⃣ Count the Number of Possible Triangles (Medium)</summary>
🔹 Brute Force Approach

Check every triplet and verify if they form a valid triangle.

Time Complexity: O(N³), Space Complexity: O(1)

🔹 Optimal Approach (Two Pointer Technique)

Sort the array. Fix one side and use two pointers to count valid triangles.

Time Complexity: O(N²), Space Complexity: O(1)

</details> <details> <summary>6️⃣ Count All Triplets with Given Sum in Sorted Array (Medium)</summary>
🔹 Brute Force Approach

Use three nested loops to find all valid triplets.

Time Complexity: O(N³), Space Complexity: O(1)

🔹 Optimal Approach (Two Pointer Technique)

Sort the array, fix one element, and use two pointers to find remaining two elements.

Time Complexity: O(N²), Space Complexity: O(1)

</details> <details> <summary>7️⃣ Container With Most Water (Medium)</summary>
🔹 Brute Force Approach

Check every pair and calculate the area.

Time Complexity: O(N²), Space Complexity: O(1)

🔹 Optimal Approach (Two Pointer Technique)

Use two pointers—one at the start and one at the end—to maximize the water stored while adjusting the shorter height.

Time Complexity: O(N), Space Complexity: O(1)

</details> <details> <summary>8️⃣ Trapping Rain Water (Medium)</summary>
🔹 Brute Force Approach

Check the max height to the left and right for each index.

Time Complexity: O(N²), Space Complexity: O(1)

🔹 Optimal Approach (Two Pointer Technique)

Use two pointers to track left and right boundaries, calculating trapped water dynamically.

Time Complexity: O(N), Space Complexity: O(1)

</details> <details> <summary>9️⃣ Single Element in Sorted Array (Medium)</summary>
🔹 Brute Force Approach

Iterate through the array and check occurrences.

Time Complexity: O(N), Space Complexity: O(1)

🔹 Optimal Approach (Binary Search + Two Pointer Idea)

Use binary search and two-pointer logic to find the single element.

Time Complexity: O(log N), Space Complexity: O(1)

</details> <details> <summary>🔟 Search in Sorted Rotated Array (Hard)</summary>
🔹 Brute Force Approach

Linear search through the entire array.

Time Complexity: O(N), Space Complexity: O(1)

🔹 Optimal Approach (Binary Search + Two Pointer Idea)

Modify binary search to handle rotation cases.

Time Complexity: O(log N), Space Complexity: O(1)

</details> <details> <summary>1️⃣1️⃣ Book Allocation (Hard)</summary>
🔹 Brute Force Approach

Try all possible allocations.

Time Complexity: O(N!), Space Complexity: O(1)

🔹 Optimal Approach (Binary Search + Two Pointer Idea)

Use binary search on answer space to minimize max pages allocated.

Time Complexity: O(N log N), Space Complexity: O(1)

</details> <details> <summary>1️⃣2️⃣ Painter’s Partition (Hard)</summary>
🔹 Brute Force Approach

Check all ways to divide boards among painters.

Time Complexity: O(N!), Space Complexity: O(1)

🔹 Optimal Approach (Binary Search + Two Pointer Idea)

Use binary search on max partition size.

Time Complexity: O(N log N), Space Complexity: O(1)

</details> <details> <summary>1️⃣3️⃣ Aggressive Cows (Hard)</summary>
🔹 Brute Force Approach

Check all possible placements.

Time Complexity: O(N²), Space Complexity: O(1)

🔹 Optimal Approach (Binary Search + Two Pointer Idea)

Use binary search on minimum distance between cows.

Time Complexity: O(N log N), Space Complexity: O(1)

</details>


---

## **📂 8. Prefix Sum**  
---    

<details>  
<summary>1️⃣ Equilibrium Index (Easy)</summary>  

&nbsp;&nbsp;🔹 **Brute Force Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Check each index and verify if the sum of elements before it equals the sum of elements after it.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N²), **Space Complexity:** O(1)  

&nbsp;&nbsp;🔹 **Optimal Approach (Prefix Sum)**  
&nbsp;&nbsp;&nbsp;&nbsp;• Precompute prefix sums. For each index `i`, check if `prefix[i-1] == totalSum - prefix[i]`.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N) (or O(1) with running sum)  

</details>  

<details>  
<summary>2️⃣ Product of Array Except Self (Easy)</summary>  

&nbsp;&nbsp;🔹 **Brute Force Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• For each element, calculate the product of all other elements by iterating over the array.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N²), **Space Complexity:** O(1)  

&nbsp;&nbsp;🔹 **Optimal Approach (Prefix & Suffix Products)**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use two arrays to store prefix and suffix products, then compute results for each index.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N) (or O(1) modifying output array)  

</details>  

<details>  
<summary>3️⃣ Longest Subarray with Equal Number of 0s and 1s (Easy)</summary>  

&nbsp;&nbsp;🔹 **Brute Force Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Check all subarrays and count occurrences of `0s` and `1s`.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N²), **Space Complexity:** O(1)  

&nbsp;&nbsp;🔹 **Optimal Approach (Prefix Sum + HashMap)**  
&nbsp;&nbsp;&nbsp;&nbsp;• Convert `0s` to `-1`, compute prefix sum, and store first occurrences in a hashmap.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>  

<details>  
<summary>4️⃣ Longest Subarray with Sum K (Medium)</summary>  

&nbsp;&nbsp;🔹 **Brute Force Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Check all subarrays and compute their sum.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N²), **Space Complexity:** O(1)  

&nbsp;&nbsp;🔹 **Optimal Approach (Prefix Sum + HashMap / Two Pointers)**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use prefix sum with a hashmap to store indices or two pointers for positive arrays.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>  

<details>  
<summary>5️⃣ Subarray Sum Divisible by K (Medium)</summary>  

&nbsp;&nbsp;🔹 **Brute Force Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Check all subarrays and compute their sum to check divisibility by `K`.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N²), **Space Complexity:** O(1)  

&nbsp;&nbsp;🔹 **Optimal Approach (Prefix Sum + Modulo HashMap)**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use prefix sum modulo `K` and store first occurrences in a hashmap.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(K)  

</details>  


---

## **📂 9. Recursion**  
---  

<details>  
<summary>1️⃣ Permutation of an Array/String (Medium)</summary>  

&nbsp;&nbsp;🔹 **Brute Force Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Generate all possible arrangements using built-in functions or simple swaps.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N!) (factorial growth), **Space Complexity:** O(N) (for recursion stack)  

&nbsp;&nbsp;🔹 **Backtracking Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Swap elements and recursively generate permutations, backtracking after each step.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N!), **Space Complexity:** O(N)  

</details>  

<details>  
<summary>2️⃣ Subsets – II (Medium)</summary>  

&nbsp;&nbsp;🔹 **Brute Force Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Generate all subsets, then filter out duplicates using a set.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(2^N * N), **Space Complexity:** O(2^N)  

&nbsp;&nbsp;🔹 **Optimized Backtracking Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Sort the array and use recursion with an index-based approach to avoid duplicates.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(2^N), **Space Complexity:** O(N) (for recursion stack)  

</details>  

<details>  
<summary>3️⃣ Combination Sum (Medium)</summary>  

&nbsp;&nbsp;🔹 **Brute Force Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Generate all possible subsets and check if they sum to the target.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(2^N * N), **Space Complexity:** O(N)  

&nbsp;&nbsp;🔹 **Backtracking Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use recursion with a decision tree (include/exclude element).  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(2^N), **Space Complexity:** O(N)  

</details>  

<details>  
<summary>4️⃣ Palindrome Partition (Medium)</summary>  

&nbsp;&nbsp;🔹 **Brute Force Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Generate all partitions and check each for palindromes.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(2^N * N), **Space Complexity:** O(N)  

&nbsp;&nbsp;🔹 **Backtracking Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Recursively partition and check palindromes dynamically.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(2^N), **Space Complexity:** O(N)  

</details>  

<details>  
<summary>5️⃣ Merge Sort (Medium)</summary>  

&nbsp;&nbsp;🔹 **Recursive Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Divide the array into two halves, recursively sort, and merge them.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N log N), **Space Complexity:** O(N)  

</details>  

<details>  
<summary>6️⃣ N Queen (Hard)</summary>  

&nbsp;&nbsp;🔹 **Brute Force Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Try placing queens in every cell and check constraints.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N^N), **Space Complexity:** O(N^2)  

&nbsp;&nbsp;🔹 **Backtracking Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Place a queen in each row and backtrack if a conflict arises.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N!), **Space Complexity:** O(N)  

</details>  

<details>  
<summary>7️⃣ Sudoku Solver (Hard)</summary>  

&nbsp;&nbsp;🔹 **Backtracking Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Try placing digits in empty spots and backtrack when needed.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(9^(N²)), **Space Complexity:** O(N²)  

</details>  

<details>  
<summary>8️⃣ Rat in a Maze (Hard)</summary>  

&nbsp;&nbsp;🔹 **Recursive Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Move in all possible directions and backtrack when needed.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(2^(N²)), **Space Complexity:** O(N²)  

</details>  

<details>  
<summary>9️⃣ Count Inversions (Hard)</summary>  

&nbsp;&nbsp;🔹 **Brute Force Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Count pairs where i < j and arr[i] > arr[j].  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N²), **Space Complexity:** O(1)  

&nbsp;&nbsp;🔹 **Merge Sort Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Count inversions while merging two halves.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N log N), **Space Complexity:** O(N)  

</details>  

<details>  
<summary>🔟 Knight’s Tour (Hard)</summary>  

&nbsp;&nbsp;🔹 **Backtracking Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Move the knight to all valid positions recursively and backtrack if stuck.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(8^(N²)), **Space Complexity:** O(N²)  

</details>  



---

## **📂 10. Linked List**  
---

<details>  
<summary>1️⃣ Reverse a Linked List (Easy)</summary>  

&nbsp;&nbsp;🔹 **Iterative Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use three pointers: `prev`, `curr`, and `next`.  
&nbsp;&nbsp;&nbsp;&nbsp;• Reverse the `next` pointer of each node to point to the previous node.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(1)  

&nbsp;&nbsp;🔹 **Recursive Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Recursively reverse the rest of the list, then fix the current node's pointer.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>2️⃣ Detect Cycle in Linked List (Easy)</summary>  

&nbsp;&nbsp;🔹 **Floyd’s Cycle Detection Algorithm (Tortoise and Hare)**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use two pointers: slow and fast.  
&nbsp;&nbsp;&nbsp;&nbsp;• Move slow by one step and fast by two steps.  
&nbsp;&nbsp;&nbsp;&nbsp;• If they meet, there is a cycle.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(1)  

&nbsp;&nbsp;🔹 **Using Hashing (Set)**  
&nbsp;&nbsp;&nbsp;&nbsp;• Store visited nodes in a set.  
&nbsp;&nbsp;&nbsp;&nbsp;• If a node is revisited, a cycle exists.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>3️⃣ Find the First Node of Loop in Linked List (Medium)</summary>  

&nbsp;&nbsp;🔹 **Floyd’s Algorithm Extension**  
&nbsp;&nbsp;&nbsp;&nbsp;• Detect cycle using slow and fast pointers.  
&nbsp;&nbsp;&nbsp;&nbsp;• Once they meet, place one pointer at head and move both one step at a time.  
&nbsp;&nbsp;&nbsp;&nbsp;• The node where they meet again is the start of the loop.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(1)  

</details>

<details>  
<summary>4️⃣ Remove Cycle from a Linked List (Medium)</summary>  

&nbsp;&nbsp;🔹 **Floyd’s + Loop Removal**  
&nbsp;&nbsp;&nbsp;&nbsp;• Detect cycle using Floyd’s method.  
&nbsp;&nbsp;&nbsp;&nbsp;• Find the start of the loop.  
&nbsp;&nbsp;&nbsp;&nbsp;• Traverse to the node just before loop start and set its `next` to `NULL`.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(1)  

</details>

<details>  
<summary>5️⃣ Merge Two Sorted Linked Lists (Medium)</summary>  

&nbsp;&nbsp;🔹 **Iterative Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use a dummy node and merge nodes in order.  
&nbsp;&nbsp;&nbsp;&nbsp;• Point the dummy’s next to the merged result.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N + M), **Space Complexity:** O(1)  

&nbsp;&nbsp;🔹 **Recursive Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Recursively choose the smaller head node and build the result.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N + M), **Space Complexity:** O(N + M)  

</details>

<details>  
<summary>6️⃣ Find Middle of a Linked List (Medium)</summary>  

&nbsp;&nbsp;🔹 **Two Pointer Technique**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use slow and fast pointers.  
&nbsp;&nbsp;&nbsp;&nbsp;• Move slow by 1 step and fast by 2 steps.  
&nbsp;&nbsp;&nbsp;&nbsp;• When fast reaches the end, slow will be at the middle.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(1)  

</details>

<details>  
<summary>7️⃣ Flatten Linked List (Medium)</summary>  

&nbsp;&nbsp;🔹 **Recursive Merge**  
&nbsp;&nbsp;&nbsp;&nbsp;• Each node has a `next` and `bottom` pointer.  
&nbsp;&nbsp;&nbsp;&nbsp;• Recursively flatten the list starting from the rightmost list.  
&nbsp;&nbsp;&nbsp;&nbsp;• Merge current list with the flattened next list.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(1)  

</details>

<details>  
<summary>8️⃣ Clone List with Next and Random Pointer (Hard)</summary>  

&nbsp;&nbsp;🔹 **Optimized Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Insert clone nodes in between original nodes.  
&nbsp;&nbsp;&nbsp;&nbsp;• Set correct random pointers for clones.  
&nbsp;&nbsp;&nbsp;&nbsp;• Separate the clone list from original.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(1)  

</details>

<details>  
<summary>9️⃣ Reverse Nodes in K-Groups (Hard)</summary>  

&nbsp;&nbsp;🔹 **Recursive Group Reversal**  
&nbsp;&nbsp;&nbsp;&nbsp;• Reverse first k nodes, then recursively call for next k nodes.  
&nbsp;&nbsp;&nbsp;&nbsp;• Connect reversed groups.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N/k)  

&nbsp;&nbsp;🔹 **Iterative Version (Harder to Implement)**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use loop to reverse k nodes at a time.  
&nbsp;&nbsp;&nbsp;&nbsp;• Manage connections between reversed segments.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(1)  

</details>

<details>  
<summary>🔟 LRU Cache (Hard)</summary>  

&nbsp;&nbsp;🔹 **Using Doubly Linked List + HashMap**  
&nbsp;&nbsp;&nbsp;&nbsp;• HashMap for O(1) access, Doubly Linked List for O(1) updates.  
&nbsp;&nbsp;&nbsp;&nbsp;• Maintain recently used items at the front.  
&nbsp;&nbsp;&nbsp;&nbsp;• Evict least recently used item when capacity is reached.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(1) for get/put, **Space Complexity:** O(capacity)  

</details>

<details>  
<summary>1️⃣1️⃣ Add Numbers in Linked List (Hard)</summary>  

&nbsp;&nbsp;🔹 **Like Adding Two Numbers Digit-by-Digit**  
&nbsp;&nbsp;&nbsp;&nbsp;• Traverse both lists, add corresponding digits with carry.  
&nbsp;&nbsp;&nbsp;&nbsp;• Create new nodes for the sum.  
&nbsp;&nbsp;&nbsp;&nbsp;• Handle final carry.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>1️⃣2️⃣ Swap Nodes in Pairs (Hard)</summary>  

&nbsp;&nbsp;🔹 **Recursive Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Swap first two nodes, then recursively swap remaining list.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

&nbsp;&nbsp;🔹 **Iterative Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use dummy node and loop to swap pairs.  
&nbsp;&nbsp;&nbsp;&nbsp;• Update pointers accordingly.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(1)  

</details>


---

## **📂 11. Stack**  
---

<details>  
<summary>1️⃣ Implement Stack (Easy)</summary>  

&nbsp;&nbsp;🔹 **Using Array or Linked List**  
&nbsp;&nbsp;&nbsp;&nbsp;• Basic stack operations: `push()`, `pop()`, `top()`, `isEmpty()`.  
&nbsp;&nbsp;&nbsp;&nbsp;• Can be implemented using dynamic array or singly linked list.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(1) for all operations  
&nbsp;&nbsp;&nbsp;&nbsp;• **Space Complexity:** O(N)  

</details>

<details>  
<summary>2️⃣ Implement Queue using Stack (Medium)</summary>  

&nbsp;&nbsp;🔹 **Using Two Stacks**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use two stacks: `inStack` for enqueue, `outStack` for dequeue.  
&nbsp;&nbsp;&nbsp;&nbsp;• When dequeuing, transfer elements from `inStack` to `outStack` if needed.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(1) amortized per operation  
&nbsp;&nbsp;&nbsp;&nbsp;• **Space Complexity:** O(N)  

</details>

<details>  
<summary>3️⃣ Valid Parenthesis (Medium)</summary>  

&nbsp;&nbsp;🔹 **Using Stack**  
&nbsp;&nbsp;&nbsp;&nbsp;• Traverse string and push opening brackets to stack.  
&nbsp;&nbsp;&nbsp;&nbsp;• For closing brackets, check for matching top in stack.  
&nbsp;&nbsp;&nbsp;&nbsp;• Stack should be empty at the end for valid string.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>4️⃣ Stock Span Problem (Medium)</summary>  

&nbsp;&nbsp;🔹 **Monotonic Stack Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Maintain a stack of indices where prices are in decreasing order.  
&nbsp;&nbsp;&nbsp;&nbsp;• For each day, find how many consecutive days before it had a lower price.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>5️⃣ Next Greater Element (Medium)</summary>  

&nbsp;&nbsp;🔹 **Stack Approach (Right to Left)**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use stack to keep track of greater elements.  
&nbsp;&nbsp;&nbsp;&nbsp;• Traverse from right and maintain decreasing stack.  
&nbsp;&nbsp;&nbsp;&nbsp;• Replace current element with top of stack (next greater), if any.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>6️⃣ Previous Smaller Element (Medium)</summary>  

&nbsp;&nbsp;🔹 **Stack Approach (Left to Right)**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use stack to track elements smaller than current.  
&nbsp;&nbsp;&nbsp;&nbsp;• If no such element, return -1 or null.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>7️⃣ Decode the String (Hard)</summary>  

&nbsp;&nbsp;🔹 **Using Stack for Characters and Counts**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use two stacks: one for numbers, one for strings.  
&nbsp;&nbsp;&nbsp;&nbsp;• On `]`, pop and build the decoded string segment.  
&nbsp;&nbsp;&nbsp;&nbsp;• Handles nested patterns like `3[a2[c]]`.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>



---

## **📂 12. Queue**  
---

<details>  
<summary>1️⃣ Implement Queue (Medium)</summary>  

&nbsp;&nbsp;🔹 **Using Array or Linked List**  
&nbsp;&nbsp;&nbsp;&nbsp;• Maintain `front` and `rear` pointers.  
&nbsp;&nbsp;&nbsp;&nbsp;• Support `enqueue`, `dequeue`, `peek`, `isEmpty`.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(1) for all operations  
&nbsp;&nbsp;&nbsp;&nbsp;• **Space Complexity:** O(N)  

</details>

<details>  
<summary>2️⃣ Implement Circular Queue (Medium)</summary>  

&nbsp;&nbsp;🔹 **Modulo-based Indexing**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use array of fixed size with circular indexing using `% size`.  
&nbsp;&nbsp;&nbsp;&nbsp;• Track size, `front`, and `rear`.  
&nbsp;&nbsp;&nbsp;&nbsp;• Prevent overflow with full/empty checks.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(1), **Space Complexity:** O(N)  

</details>

<details>  
<summary>3️⃣ Implement Stack using Queue (Medium)</summary>  

&nbsp;&nbsp;🔹 **Two Queue Method**  
&nbsp;&nbsp;&nbsp;&nbsp;• Push in `q1`, and move all elements to `q2` during pop.  
&nbsp;&nbsp;&nbsp;&nbsp;• Alternatively, for optimized push, rotate `q1` each time after pushing.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(1) push, O(N) pop (or vice versa)  
&nbsp;&nbsp;&nbsp;&nbsp;• **Space Complexity:** O(N)  

</details>

<details>  
<summary>4️⃣ First Unique Character in a String (Medium)</summary>  

&nbsp;&nbsp;🔹 **Using Queue + Frequency Map**  
&nbsp;&nbsp;&nbsp;&nbsp;• Count frequency of each character.  
&nbsp;&nbsp;&nbsp;&nbsp;• Traverse string and push characters into queue.  
&nbsp;&nbsp;&nbsp;&nbsp;• Remove from queue until front is unique.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(1) (only lowercase letters)  

</details>

<details>  
<summary>5️⃣ K-sized Subarray Maximum (Medium)</summary>  

&nbsp;&nbsp;🔹 **Monotonic Deque Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use deque to store indices in decreasing order of values.  
&nbsp;&nbsp;&nbsp;&nbsp;• Remove elements out of window and smaller than current.  
&nbsp;&nbsp;&nbsp;&nbsp;• Front of deque gives max in window.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(K)  

</details>

<details>  
<summary>6️⃣ Longest Bounded-Difference Subarray (Medium)</summary>  

&nbsp;&nbsp;🔹 **Sliding Window + Monotonic Queues**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use two deques to track max and min in the window.  
&nbsp;&nbsp;&nbsp;&nbsp;• Shrink window if max - min exceeds limit.  
&nbsp;&nbsp;&nbsp;&nbsp;• Keep track of the longest valid window.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>


---

## **📂 13. Dynamic Programming (DP)**  
---

<details>  
<summary>1️⃣ Frog Jump (Hard)</summary>  

&nbsp;&nbsp;🔹 **Recursive + Memoization**  
&nbsp;&nbsp;&nbsp;&nbsp;• From stone `i`, jump to `i+1` or `i+2` with energy cost.  
&nbsp;&nbsp;&nbsp;&nbsp;• Memoize to avoid recomputation.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>2️⃣ House Robber (Hard)</summary>  

&nbsp;&nbsp;🔹 **DP on Array**  
&nbsp;&nbsp;&nbsp;&nbsp;• Choose to rob current or skip and take max of previous decisions.  
&nbsp;&nbsp;&nbsp;&nbsp;• `dp[i] = max(dp[i-1], dp[i-2] + nums[i])`  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>3️⃣ Ninjas Training (Hard)</summary>  

&nbsp;&nbsp;🔹 **DP on Day × Last Task**  
&nbsp;&nbsp;&nbsp;&nbsp;• Cannot repeat same task on consecutive days.  
&nbsp;&nbsp;&nbsp;&nbsp;• Try all tasks except last one and memoize.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N × 4 × 3), **Space Complexity:** O(N × 4)  

</details>

<details>  
<summary>4️⃣ Grid Unique Paths (Hard)</summary>  

&nbsp;&nbsp;🔹 **DP from Destination**  
&nbsp;&nbsp;&nbsp;&nbsp;• Each cell can be reached from top or left.  
&nbsp;&nbsp;&nbsp;&nbsp;• `dp[i][j] = dp[i-1][j] + dp[i][j-1]`  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(M×N), **Space Complexity:** O(M×N)  

</details>

<details>  
<summary>5️⃣ Minimum Path Sum in Grid (Hard)</summary>  

&nbsp;&nbsp;🔹 **DP with Cost**  
&nbsp;&nbsp;&nbsp;&nbsp;• Add current cell value to min of top/left.  
&nbsp;&nbsp;&nbsp;&nbsp;• `dp[i][j] = grid[i][j] + min(dp[i-1][j], dp[i][j-1])`  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(M×N), **Space Complexity:** O(M×N)  

</details>

<details>  
<summary>6️⃣ Maximum Path Sum in Matrix (Hard)</summary>  

&nbsp;&nbsp;🔹 **Bottom-Up DP**  
&nbsp;&nbsp;&nbsp;&nbsp;• From cell `(i, j)`, move to `(i+1, j±1)` or `(i+1, j)`  
&nbsp;&nbsp;&nbsp;&nbsp;• Keep max path sum at each cell.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N²), **Space Complexity:** O(N²)  

</details>

<details>  
<summary>7️⃣ Subset Sum Equals to K (Hard)</summary>  

&nbsp;&nbsp;🔹 **Classic DP Problem**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use `dp[i][target]` to check if target can be formed.  
&nbsp;&nbsp;&nbsp;&nbsp;• Either pick or not pick the element.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N×K), **Space Complexity:** O(N×K)  

</details>

<details>  
<summary>8️⃣ Equal Partition (Hard)</summary>  

&nbsp;&nbsp;🔹 **Use Subset Sum**  
&nbsp;&nbsp;&nbsp;&nbsp;• If sum is odd, return false.  
&nbsp;&nbsp;&nbsp;&nbsp;• Else check if `sum/2` subset exists using DP.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N×Sum), **Space Complexity:** O(N×Sum)  

</details>

<details>  
<summary>9️⃣ Buy & Sell Stock (Max K Transactions) (Hard)</summary>  

&nbsp;&nbsp;🔹 **3D DP: day, transaction, holding**  
&nbsp;&nbsp;&nbsp;&nbsp;• Memoize decision to buy/sell/skip.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N×K×2), **Space Complexity:** O(N×K×2)  

</details>

<details>  
<summary>🔟 0/1 Knapsack (Hard)</summary>  

&nbsp;&nbsp;🔹 **Pick or Skip Item**  
&nbsp;&nbsp;&nbsp;&nbsp;• If `wt[i] <= W`, then `dp[i][W] = max(val[i] + dp[i-1][W-wt[i]], dp[i-1][W])`  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N×W), **Space Complexity:** O(N×W)  

</details>

<details>  
<summary>1️⃣1️⃣ Coin Change 2 (Hard)</summary>  

&nbsp;&nbsp;🔹 **Unbounded Knapsack Style**  
&nbsp;&nbsp;&nbsp;&nbsp;• `dp[i][target] = dp[i-1][target] + dp[i][target - coin[i]]`  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N×Amount), **Space Complexity:** O(N×Amount)  

</details>

<details>  
<summary>1️⃣2️⃣ Rod Cutting (Hard)</summary>  

&nbsp;&nbsp;🔹 **Unbounded Knapsack**  
&nbsp;&nbsp;&nbsp;&nbsp;• Choose to cut or skip each length.  
&nbsp;&nbsp;&nbsp;&nbsp;• Maximize total value.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N×L), **Space Complexity:** O(N×L)  

</details>

<details>  
<summary>1️⃣3️⃣ Longest Common Subsequence (Hard)</summary>  

&nbsp;&nbsp;🔹 **Classic DP**  
&nbsp;&nbsp;&nbsp;&nbsp;• If characters match: `1 + dp[i-1][j-1]`  
&nbsp;&nbsp;&nbsp;&nbsp;• Else: `max(dp[i-1][j], dp[i][j-1])`  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(M×N), **Space Complexity:** O(M×N)  

</details>

<details>  
<summary>1️⃣4️⃣ Shortest Common Supersequence (Hard)</summary>  

&nbsp;&nbsp;🔹 **Using LCS**  
&nbsp;&nbsp;&nbsp;&nbsp;• `Length = m + n - LCS`  
&nbsp;&nbsp;&nbsp;&nbsp;• Build the sequence by merging both strings using LCS info.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(M×N), **Space Complexity:** O(M×N)  

</details>

<details>  
<summary>1️⃣5️⃣ Distinct Subsequences (Hard)</summary>  

&nbsp;&nbsp;🔹 **2D DP Table**  
&nbsp;&nbsp;&nbsp;&nbsp;• If chars match: `dp[i][j] = dp[i-1][j-1] + dp[i-1][j]`  
&nbsp;&nbsp;&nbsp;&nbsp;• Else: `dp[i][j] = dp[i-1][j]`  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(M×N), **Space Complexity:** O(M×N)  

</details>

<details>  
<summary>1️⃣6️⃣ Minimum Edit Distance (Hard)</summary>  

&nbsp;&nbsp;🔹 **DP Table for Operations**  
&nbsp;&nbsp;&nbsp;&nbsp;• Convert string A to B using insert, delete, or replace.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(M×N), **Space Complexity:** O(M×N)  

</details>

<details>  
<summary>1️⃣7️⃣ Wildcard Pattern Matching (Hard)</summary>  

&nbsp;&nbsp;🔹 **DP with Star Handling**  
&nbsp;&nbsp;&nbsp;&nbsp;• `*` matches zero/more, `?` matches one char.  
&nbsp;&nbsp;&nbsp;&nbsp;• Recursive with memoization or tabulation.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(M×N), **Space Complexity:** O(M×N)  

</details>

<details>  
<summary>1️⃣8️⃣ Buy & Sell Stock – I (Hard)</summary>  

&nbsp;&nbsp;🔹 **Single Pass**  
&nbsp;&nbsp;&nbsp;&nbsp;• Track min price and max profit on the go.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(1)  

</details>

<details>  
<summary>1️⃣9️⃣ Buy & Sell Stock – II (Hard)</summary>  

&nbsp;&nbsp;🔹 **Multiple Transactions Allowed**  
&nbsp;&nbsp;&nbsp;&nbsp;• Buy low, sell high greedily when profit is positive.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(1)  

</details>

<details>  
<summary>2️⃣0️⃣ Buy & Sell Stock – III (Hard)</summary>  

&nbsp;&nbsp;🔹 **DP with At Most 2 Transactions**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use states for day, transactions left, and holding or not.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N×K), **Space Complexity:** O(N×K)  

</details>

<details>  
<summary>2️⃣1️⃣ Matrix Chain Multiplication (Hard)</summary>  

&nbsp;&nbsp;🔹 **Parenthesization DP**  
&nbsp;&nbsp;&nbsp;&nbsp;• Try all partitions to minimize total multiplications.  
&nbsp;&nbsp;&nbsp;&nbsp;• `dp[i][j] = min(dp[i][k] + dp[k+1][j] + cost)`  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N³), **Space Complexity:** O(N²)  

</details>



---

## **📂 14. Greedy Techniques**  
---

<details>  
<summary>1️⃣ Assign Cookies (Easy)</summary>  

&nbsp;&nbsp;🔹 **Greedy Sort Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Sort both greed factor and cookie sizes.  
&nbsp;&nbsp;&nbsp;&nbsp;• Assign smallest sufficient cookie to each child.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N log N), **Space Complexity:** O(1)  

</details>

<details>  
<summary>2️⃣ Lemonade Change (Easy)</summary>  

&nbsp;&nbsp;🔹 **Track $5 and $10 Bills**  
&nbsp;&nbsp;&nbsp;&nbsp;• Greedily give change using higher denominations.  
&nbsp;&nbsp;&nbsp;&nbsp;• Return false if change can't be given.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(1)  

</details>

<details>  
<summary>3️⃣ Shortest Job First (Medium)</summary>  

&nbsp;&nbsp;🔹 **Sort by Job Duration**  
&nbsp;&nbsp;&nbsp;&nbsp;• Greedily pick the job with the least burst time.  
&nbsp;&nbsp;&nbsp;&nbsp;• Can use priority queue for dynamic insertion.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N log N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>4️⃣ Jump Game I (Medium)</summary>  

&nbsp;&nbsp;🔹 **Track Farthest Reachable Index**  
&nbsp;&nbsp;&nbsp;&nbsp;• At each index, update max reachable.  
&nbsp;&nbsp;&nbsp;&nbsp;• If index > maxReach, return false.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(1)  

</details>

<details>  
<summary>5️⃣ Jump Game II (Medium)</summary>  

&nbsp;&nbsp;🔹 **Greedy with Level Tracking**  
&nbsp;&nbsp;&nbsp;&nbsp;• Track jumps, current end, and farthest reach.  
&nbsp;&nbsp;&nbsp;&nbsp;• Increase jump when reaching current end.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(1)  

</details>

<details>  
<summary>6️⃣ Job Sequencing (Medium)</summary>  

&nbsp;&nbsp;🔹 **Sort by Profit, Greedy Slot Filling**  
&nbsp;&nbsp;&nbsp;&nbsp;• Sort jobs by profit descending.  
&nbsp;&nbsp;&nbsp;&nbsp;• Try placing each job in the latest possible slot.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N log N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>7️⃣ N Meetings in One Room (Medium)</summary>  

&nbsp;&nbsp;🔹 **Sort by Meeting End Time**  
&nbsp;&nbsp;&nbsp;&nbsp;• Greedily select meetings that end earliest.  
&nbsp;&nbsp;&nbsp;&nbsp;• Track end time of last included meeting.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N log N), **Space Complexity:** O(1)  

</details>

<details>  
<summary>8️⃣ Non-overlapping Intervals (Medium)</summary>  

&nbsp;&nbsp;🔹 **Sort by End Time**  
&nbsp;&nbsp;&nbsp;&nbsp;• Greedily keep interval that ends earliest.  
&nbsp;&nbsp;&nbsp;&nbsp;• Remove overlapping intervals.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N log N), **Space Complexity:** O(1)  

</details>

<details>  
<summary>9️⃣ Merge Non-overlapping Intervals (Medium)</summary>  

&nbsp;&nbsp;🔹 **Sort & Merge Overlaps**  
&nbsp;&nbsp;&nbsp;&nbsp;• Sort intervals by start time.  
&nbsp;&nbsp;&nbsp;&nbsp;• Merge if current overlaps with previous.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N log N), **Space Complexity:** O(N)  

</details>


---

## **📂 15. Bit Manipulation**  
---

<details>  
<summary>1️⃣ Swap Two Numbers (Easy)</summary>  

&nbsp;&nbsp;🔹 **Using XOR**  
&nbsp;&nbsp;&nbsp;&nbsp;• `a = a ^ b`, `b = a ^ b`, `a = a ^ b`  
&nbsp;&nbsp;&nbsp;&nbsp;• No temporary variable needed.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(1), **Space Complexity:** O(1)  

</details>

<details>  
<summary>2️⃣ Check if i-th Bit is Set (Easy)</summary>  

&nbsp;&nbsp;🔹 **Bitwise AND**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use `(n & (1 << i)) != 0`  
&nbsp;&nbsp;&nbsp;&nbsp;• Returns true if i-th bit is 1.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(1), **Space Complexity:** O(1)  

</details>

<details>  
<summary>3️⃣ Set i-th Bit (Easy)</summary>  

&nbsp;&nbsp;🔹 **Bitwise OR**  
&nbsp;&nbsp;&nbsp;&nbsp;• `n | (1 << i)` sets the i-th bit to 1.  
&nbsp;&nbsp;&nbsp;&nbsp;• Leaves all other bits unchanged.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(1), **Space Complexity:** O(1)  

</details>

<details>  
<summary>4️⃣ Remove i-th Bit (Medium)</summary>  

&nbsp;&nbsp;🔹 **Bitwise AND with NOT**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use `n & ~(1 << i)`  
&nbsp;&nbsp;&nbsp;&nbsp;• Clears the i-th bit.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(1), **Space Complexity:** O(1)  

</details>

<details>  
<summary>5️⃣ Toggle i-th Bit (Medium)</summary>  

&nbsp;&nbsp;🔹 **Bitwise XOR**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use `n ^ (1 << i)` to flip the i-th bit.  
&nbsp;&nbsp;&nbsp;&nbsp;• If 1 becomes 0, and vice versa.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(1), **Space Complexity:** O(1)  

</details>

<details>  
<summary>6️⃣ Remove Last Set Bit (Medium)</summary>  

&nbsp;&nbsp;🔹 **Use n & (n - 1)**  
&nbsp;&nbsp;&nbsp;&nbsp;• Clears the lowest set bit.  
&nbsp;&nbsp;&nbsp;&nbsp;• Example: `12 (1100) → 8 (1000)`  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(1), **Space Complexity:** O(1)  

</details>

<details>  
<summary>7️⃣ Count Number of Set Bits (Medium)</summary>  

&nbsp;&nbsp;🔹 **Brian Kernighan’s Algo**  
&nbsp;&nbsp;&nbsp;&nbsp;• While `n != 0`, do `n = n & (n - 1)` and count iterations.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(# of set bits), **Space Complexity:** O(1)  

</details>

<details>  
<summary>8️⃣ Power of 2 or Not (Medium)</summary>  

&nbsp;&nbsp;🔹 **Check Single Set Bit**  
&nbsp;&nbsp;&nbsp;&nbsp;• `n > 0` and `n & (n - 1) == 0`  
&nbsp;&nbsp;&nbsp;&nbsp;• Only powers of 2 have one bit set.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(1), **Space Complexity:** O(1)  

</details>

<details>  
<summary>9️⃣ Single Number I (Medium)</summary>  

&nbsp;&nbsp;🔹 **Using XOR**  
&nbsp;&nbsp;&nbsp;&nbsp;• XOR of all elements gives the unique one.  
&nbsp;&nbsp;&nbsp;&nbsp;• All pairs cancel out.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(1)  

</details>

<details>  
<summary>🔟 Single Number II (Medium)</summary>  

&nbsp;&nbsp;🔹 **Bit Counting by Position**  
&nbsp;&nbsp;&nbsp;&nbsp;• Count 1s at each bit position.  
&nbsp;&nbsp;&nbsp;&nbsp;• Take modulo 3 to isolate the unique number.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(32N), **Space Complexity:** O(1)  

</details>



---

## **📂 16. Tree**  
---

<details>  
<summary>1️⃣ Inorder Traversal (Easy)</summary>  

&nbsp;&nbsp;🔹 **Recursive Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Traverse Left → Node → Right.  
&nbsp;&nbsp;&nbsp;&nbsp;• Base case: null node.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(H)  

</details>

<details>  
<summary>2️⃣ Preorder Traversal (Easy)</summary>  

&nbsp;&nbsp;🔹 **Recursive Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Traverse Node → Left → Right.  
&nbsp;&nbsp;&nbsp;&nbsp;• Use for cloning or copying trees.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(H)  

</details>

<details>  
<summary>3️⃣ Postorder Traversal (Easy)</summary>  

&nbsp;&nbsp;🔹 **Recursive Approach**  
&nbsp;&nbsp;&nbsp;&nbsp;• Traverse Left → Right → Node.  
&nbsp;&nbsp;&nbsp;&nbsp;• Useful in deleting trees.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(H)  

</details>

<details>  
<summary>4️⃣ Level Order Traversal (Medium)</summary>  

&nbsp;&nbsp;🔹 **Using Queue**  
&nbsp;&nbsp;&nbsp;&nbsp;• Traverse level by level using BFS.  
&nbsp;&nbsp;&nbsp;&nbsp;• Enqueue children of each node.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>5️⃣ In, Pre, Post Traversal Using Stack (Medium)</summary>  

&nbsp;&nbsp;🔹 **Iterative Traversals**  
&nbsp;&nbsp;&nbsp;&nbsp;• Simulate recursion using explicit stack.  
&nbsp;&nbsp;&nbsp;&nbsp;• Preorder: process node before children.  
&nbsp;&nbsp;&nbsp;&nbsp;• Postorder: process node after both children.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>6️⃣ Maximum Depth of Binary Tree (Medium)</summary>  

&nbsp;&nbsp;🔹 **DFS Recursion**  
&nbsp;&nbsp;&nbsp;&nbsp;• Depth = 1 + max(leftDepth, rightDepth)  
&nbsp;&nbsp;&nbsp;&nbsp;• Base case: null → 0  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(H)  

</details>

<details>  
<summary>7️⃣ Check for Balanced Binary Tree (Medium)</summary>  

&nbsp;&nbsp;🔹 **Postorder Check with Height**  
&nbsp;&nbsp;&nbsp;&nbsp;• For each node, check height diff ≤ 1  
&nbsp;&nbsp;&nbsp;&nbsp;• Return -1 if unbalanced  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(H)  

</details>

<details>  
<summary>8️⃣ Diameter of Binary Tree (Medium)</summary>  

&nbsp;&nbsp;🔹 **Max Path Through Any Node**  
&nbsp;&nbsp;&nbsp;&nbsp;• Diameter = max(leftHeight + rightHeight)  
&nbsp;&nbsp;&nbsp;&nbsp;• Track max at each recursion.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(H)  

</details>

<details>  
<summary>9️⃣ Maximum Path Sum (Medium)</summary>  

&nbsp;&nbsp;🔹 **Postorder DFS + Global Max**  
&nbsp;&nbsp;&nbsp;&nbsp;• Calculate max gain from left/right subtrees.  
&nbsp;&nbsp;&nbsp;&nbsp;• Update global max with left + node + right.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(H)  

</details>

<details>  
<summary>🔟 Check If Two Trees Are Identical (Medium)</summary>  

&nbsp;&nbsp;🔹 **Recursive Compare**  
&nbsp;&nbsp;&nbsp;&nbsp;• Base case: both null → true  
&nbsp;&nbsp;&nbsp;&nbsp;• Compare node values and children recursively  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(H)  

</details>

<details>  
<summary>1️⃣1️⃣ Spiral Traversal of Tree (Medium)</summary>  

&nbsp;&nbsp;🔹 **Zigzag Level Order**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use two stacks or deque  
&nbsp;&nbsp;&nbsp;&nbsp;• Alternate direction each level  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>



---

## **📂 17. Graph**  
---

<details>  
<summary>1️⃣ Graph Representation (Easy)</summary>  

&nbsp;&nbsp;🔹 **Adjacency List**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use a vector of lists/maps.  
&nbsp;&nbsp;&nbsp;&nbsp;• Good for sparse graphs.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(1) for add edge, **Space:** O(V + E)  

&nbsp;&nbsp;🔹 **Adjacency Matrix**  
&nbsp;&nbsp;&nbsp;&nbsp;• 2D array `adj[V][V]`  
&nbsp;&nbsp;&nbsp;&nbsp;• Good for dense graphs.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(1) access, **Space:** O(V²)  

</details>

<details>  
<summary>2️⃣ Breadth-First Search (BFS) (Medium)</summary>  

&nbsp;&nbsp;🔹 **Using Queue**  
&nbsp;&nbsp;&nbsp;&nbsp;• Explore level by level.  
&nbsp;&nbsp;&nbsp;&nbsp;• Use visited array to prevent cycles.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(V + E), **Space Complexity:** O(V)  

</details>

<details>  
<summary>3️⃣ Depth-First Search (DFS) (Medium)</summary>  

&nbsp;&nbsp;🔹 **Recursive or Stack**  
&nbsp;&nbsp;&nbsp;&nbsp;• Explore depth before breadth.  
&nbsp;&nbsp;&nbsp;&nbsp;• Mark nodes visited.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(V + E), **Space Complexity:** O(V)  

</details>

<details>  
<summary>4️⃣ Detect Cycle in Undirected Graph (Medium)</summary>  

&nbsp;&nbsp;🔹 **Using DFS with Parent Check**  
&nbsp;&nbsp;&nbsp;&nbsp;• If a visited node is not parent, cycle exists.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(V + E), **Space Complexity:** O(V)  

</details>

<details>  
<summary>5️⃣ Detect Cycle in Directed Graph (Medium)</summary>  

&nbsp;&nbsp;🔹 **DFS + Recursion Stack**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use visited and recursion stack.  
&nbsp;&nbsp;&nbsp;&nbsp;• Cycle exists if node is revisited in current stack.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(V + E), **Space Complexity:** O(V)  

</details>

<details>  
<summary>6️⃣ Topological Sort (Medium)</summary>  

&nbsp;&nbsp;🔹 **Using DFS or Kahn’s Algo**  
&nbsp;&nbsp;&nbsp;&nbsp;• Only for Directed Acyclic Graphs (DAGs).  
&nbsp;&nbsp;&nbsp;&nbsp;• Kahn’s: Use indegree and queue.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(V + E), **Space Complexity:** O(V)  

</details>

<details>  
<summary>7️⃣ Number of Connected Components (Medium)</summary>  

&nbsp;&nbsp;🔹 **DFS or BFS on All Nodes**  
&nbsp;&nbsp;&nbsp;&nbsp;• Count how many DFS/BFS calls needed.  
&nbsp;&nbsp;&nbsp;&nbsp;• Unvisited node means new component.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(V + E), **Space Complexity:** O(V)  

</details>

<details>  
<summary>8️⃣ Bipartite Graph Check (Medium)</summary>  

&nbsp;&nbsp;🔹 **BFS with Coloring**  
&nbsp;&nbsp;&nbsp;&nbsp;• Color neighbors opposite.  
&nbsp;&nbsp;&nbsp;&nbsp;• If conflict, it's not bipartite.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(V + E), **Space Complexity:** O(V)  

</details>

<details>  
<summary>9️⃣ Dijkstra’s Algorithm (Medium)</summary>  

&nbsp;&nbsp;🔹 **Priority Queue + Distance Array**  
&nbsp;&nbsp;&nbsp;&nbsp;• Greedily pick the shortest path node.  
&nbsp;&nbsp;&nbsp;&nbsp;• Works with non-negative weights.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O((V + E) log V), **Space Complexity:** O(V)  

</details>

<details>  
<summary>🔟 Detect Cycle Using Union-Find (Medium)</summary>  

&nbsp;&nbsp;🔹 **Disjoint Set Union (DSU)**  
&nbsp;&nbsp;&nbsp;&nbsp;• For undirected graphs.  
&nbsp;&nbsp;&nbsp;&nbsp;• If u and v have same parent → cycle.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(E * α(V)), **Space Complexity:** O(V)  

</details>




---

## **📂 18. Heap**  
---

<details>  
<summary>1️⃣ K'th Missing Positive Number (Medium)</summary>  

&nbsp;&nbsp;🔹 **Binary Search or Linear Count**  
&nbsp;&nbsp;&nbsp;&nbsp;• Count missing numbers at each index.  
&nbsp;&nbsp;&nbsp;&nbsp;• Binary search on index for efficiency.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(log N), **Space Complexity:** O(1)  

</details>

<details>  
<summary>2️⃣ Find K Pairs with Smallest Sums (Medium)</summary>  

&nbsp;&nbsp;🔹 **Min Heap of Pairs**  
&nbsp;&nbsp;&nbsp;&nbsp;• Push initial pairs into heap.  
&nbsp;&nbsp;&nbsp;&nbsp;• Pop k smallest and push next candidates.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(K log K), **Space Complexity:** O(K)  

</details>

<details>  
<summary>3️⃣ K'th Smallest Element in a Sorted Matrix (Medium)</summary>  

&nbsp;&nbsp;🔹 **Min Heap + Binary Search**  
&nbsp;&nbsp;&nbsp;&nbsp;• Push first row elements into heap.  
&nbsp;&nbsp;&nbsp;&nbsp;• Extract min and insert next in row.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(K log N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>4️⃣ K'th Largest Sum of Contiguous Subarray (Medium)</summary>  

&nbsp;&nbsp;🔹 **Prefix Sums + Min Heap**  
&nbsp;&nbsp;&nbsp;&nbsp;• Generate all subarray sums.  
&nbsp;&nbsp;&nbsp;&nbsp;• Maintain heap of size K.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N² log K), **Space Complexity:** O(K)  

</details>

<details>  
<summary>5️⃣ K Closest Points to Origin (Medium)</summary>  

&nbsp;&nbsp;🔹 **Max Heap of Size K**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use distance squared to compare.  
&nbsp;&nbsp;&nbsp;&nbsp;• Keep heap of K closest points.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N log K), **Space Complexity:** O(K)  

</details>

<details>  
<summary>6️⃣ Find K Closest Elements in Sorted Array (Medium)</summary>  

&nbsp;&nbsp;🔹 **Binary Search + Two Pointers**  
&nbsp;&nbsp;&nbsp;&nbsp;• Find insertion point of target.  
&nbsp;&nbsp;&nbsp;&nbsp;• Expand left/right to pick K elements.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(log N + K), **Space Complexity:** O(1)  

</details>

<details>  
<summary>7️⃣ Rearrange String K Distance Apart (Medium)</summary>  

&nbsp;&nbsp;🔹 **Max Heap + Queue**  
&nbsp;&nbsp;&nbsp;&nbsp;• Greedily pick highest freq char.  
&nbsp;&nbsp;&nbsp;&nbsp;• Use queue to enforce K distance.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N log K), **Space Complexity:** O(N)  

</details>

<details>  
<summary>8️⃣ Find Median from Data Stream (Medium)</summary>  

&nbsp;&nbsp;🔹 **Max Heap + Min Heap**  
&nbsp;&nbsp;&nbsp;&nbsp;• Max heap for left half, min heap for right.  
&nbsp;&nbsp;&nbsp;&nbsp;• Balance heaps after each insert.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(log N) per insert, **Space Complexity:** O(N)  

</details>

<details>  
<summary>9️⃣ K'th Smallest Prime Fraction (Medium)</summary>  

&nbsp;&nbsp;🔹 **Min Heap of Fractions**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use heap to compare fractions a/b.  
&nbsp;&nbsp;&nbsp;&nbsp;• Push next possible fractions by column.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(K log N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>🔟 Divide Array into K Sets of Consecutive Numbers (Medium)</summary>  

&nbsp;&nbsp;🔹 **Min Heap + Frequency Map**  
&nbsp;&nbsp;&nbsp;&nbsp;• Count frequency, use min heap for order.  
&nbsp;&nbsp;&nbsp;&nbsp;• Check and reduce counts for k consecutive numbers.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N log N), **Space Complexity:** O(N)  
</details>


---

## **📂 19. Tries**  
---

<details>  
<summary>1️⃣ Implement Trie - I (Easy)</summary>  

&nbsp;&nbsp;🔹 **Basic Trie Structure**  
&nbsp;&nbsp;&nbsp;&nbsp;• Support `insert()` and `search()` methods.  
&nbsp;&nbsp;&nbsp;&nbsp;• Use HashMap or array of 26 for children.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>2️⃣ Implement Trie - II (Easy)</summary>  

&nbsp;&nbsp;🔹 **Add `startsWith()` to Basic Trie**  
&nbsp;&nbsp;&nbsp;&nbsp;• Check if any word in the trie starts with prefix.  
&nbsp;&nbsp;&nbsp;&nbsp;• Same structure, additional method.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>3️⃣ Search Suggestions System (Easy)</summary>  

&nbsp;&nbsp;🔹 **Trie + DFS/MinHeap**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use trie to store products.  
&nbsp;&nbsp;&nbsp;&nbsp;• DFS to collect suggestions after prefix match.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(M·N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>4️⃣ Longest Common Prefix Using Trie (Easy)</summary>  

&nbsp;&nbsp;🔹 **Insert All Strings into Trie**  
&nbsp;&nbsp;&nbsp;&nbsp;• Traverse till only one child exists and no end-of-word.  
&nbsp;&nbsp;&nbsp;&nbsp;• Return built prefix.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N·M), **Space Complexity:** O(N·M)  

</details>

<details>  
<summary>5️⃣ Count Words in a Trie (Easy)</summary>  

&nbsp;&nbsp;🔹 **Add Word Count at End Nodes**  
&nbsp;&nbsp;&nbsp;&nbsp;• Add a counter at each node for inserted words.  
&nbsp;&nbsp;&nbsp;&nbsp;• Update count during insert.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>6️⃣ Word Search II (Trie + Backtracking) (Medium)</summary>  

&nbsp;&nbsp;🔹 **Trie + DFS**  
&nbsp;&nbsp;&nbsp;&nbsp;• Build trie of words.  
&nbsp;&nbsp;&nbsp;&nbsp;• DFS from each board cell checking valid paths in trie.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(M·N·4^L), **Space Complexity:** O(W·L)  

</details>

<details>  
<summary>7️⃣ Maximum XOR of Two Numbers in an Array (Trie) (Medium)</summary>  

&nbsp;&nbsp;🔹 **Bitwise Trie**  
&nbsp;&nbsp;&nbsp;&nbsp;• Insert binary form of numbers into trie.  
&nbsp;&nbsp;&nbsp;&nbsp;• Try to pick opposite bits for max XOR.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>8️⃣ Replace Words (Using Dictionary Trie) (Medium)</summary>  

&nbsp;&nbsp;🔹 **Insert Dictionary Roots into Trie**  
&nbsp;&nbsp;&nbsp;&nbsp;• For each word, check shortest root in trie.  
&nbsp;&nbsp;&nbsp;&nbsp;• Replace word with root if found.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N·M), **Space Complexity:** O(N)  

</details>

<details>  
<summary>9️⃣ Design Search Autocomplete System (Hard)</summary>  

&nbsp;&nbsp;🔹 **Trie + Priority Queue + Frequency Map**  
&nbsp;&nbsp;&nbsp;&nbsp;• Track frequency of words.  
&nbsp;&nbsp;&nbsp;&nbsp;• On input char, search trie and rank top matches.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(P log N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>🔟 Concatenated Words (Trie + DFS) (Hard)</summary>  

&nbsp;&nbsp;🔹 **Insert Words into Trie, DFS to Build**  
&nbsp;&nbsp;&nbsp;&nbsp;• Try splitting words into valid trie parts.  
&nbsp;&nbsp;&nbsp;&nbsp;• Avoid using the word itself during DFS.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N·L²), **Space Complexity:** O(N·L)  

</details>



---

## **📂 20. Segment Tree & Fenwick Tree**  
---

<details>  
<summary>1️⃣ Range Sum Query (Immutable) - Easy</summary>  

&nbsp;&nbsp;🔹 **Prefix Sum Array**  
&nbsp;&nbsp;&nbsp;&nbsp;• Precompute cumulative sums.  
&nbsp;&nbsp;&nbsp;&nbsp;• Return difference of prefix sums.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(1), **Space Complexity:** O(N)  

</details>

<details>  
<summary>2️⃣ Range Sum Query (Mutable) - Medium</summary>  

&nbsp;&nbsp;🔹 **Fenwick Tree / Segment Tree**  
&nbsp;&nbsp;&nbsp;&nbsp;• Efficient update and query on range sums.  
&nbsp;&nbsp;&nbsp;&nbsp;• Use Fenwick Tree or Segment Tree.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(log N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>3️⃣ Range Minimum Query - Medium</summary>  

&nbsp;&nbsp;🔹 **Segment Tree for RMQ**  
&nbsp;&nbsp;&nbsp;&nbsp;• Build tree for minimum values.  
&nbsp;&nbsp;&nbsp;&nbsp;• Query and update efficiently.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(log N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>4️⃣ Inversion Count Using BIT - Medium</summary>  

&nbsp;&nbsp;🔹 **Count Elements Greater on Left**  
&nbsp;&nbsp;&nbsp;&nbsp;• Use BIT to count how many elements are greater to the left.  
&nbsp;&nbsp;&nbsp;&nbsp;• Coordinate compression might be needed.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N log N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>5️⃣ Count of Smaller Numbers After Self - Hard</summary>  

&nbsp;&nbsp;🔹 **Use BIT or Segment Tree**  
&nbsp;&nbsp;&nbsp;&nbsp;• Traverse from right to left.  
&nbsp;&nbsp;&nbsp;&nbsp;• Use tree to maintain frequency count.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N log N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>6️⃣ K-th Smallest Number After Updates - Hard</summary>  

&nbsp;&nbsp;🔹 **Segment Tree with Order Statistics**  
&nbsp;&nbsp;&nbsp;&nbsp;• Maintain frequency tree.  
&nbsp;&nbsp;&nbsp;&nbsp;• Binary search with prefix sums.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(log² N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>7️⃣ Range Sum of Sorted Subarray Sums - Hard</summary>  

&nbsp;&nbsp;🔹 **Fenwick Tree + Sorting**  
&nbsp;&nbsp;&nbsp;&nbsp;• Compute all subarray sums, sort and prefix sum.  
&nbsp;&nbsp;&nbsp;&nbsp;• Efficient retrieval using BIT.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N² log N), **Space Complexity:** O(N²)  

</details>

<details>  
<summary>8️⃣ Number of Range Sum - Hard</summary>  

&nbsp;&nbsp;🔹 **Segment Tree / Binary Indexed Tree + Prefix Sums**  
&nbsp;&nbsp;&nbsp;&nbsp;• Count prefix sums in given range using BIT.  
&nbsp;&nbsp;&nbsp;&nbsp;• Coordinate compression needed.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(N log N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>9️⃣ Dynamic Range Sum Queries - Medium</summary>  

&nbsp;&nbsp;🔹 **Segment Tree / Fenwick Tree**  
&nbsp;&nbsp;&nbsp;&nbsp;• Support range update and point query.  
&nbsp;&nbsp;&nbsp;&nbsp;• Lazy propagation if necessary.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(log N), **Space Complexity:** O(N)  

</details>

<details>  
<summary>🔟 2D Range Sum Query - Medium</summary>  

&nbsp;&nbsp;🔹 **2D Binary Indexed Tree**  
&nbsp;&nbsp;&nbsp;&nbsp;• Extend BIT to 2D grid.  
&nbsp;&nbsp;&nbsp;&nbsp;• Each update/query involves log² N time.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Time Complexity:** O(log² N), **Space Complexity:** O(N²)  

</details>

