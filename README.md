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
17. **Tries**
18. **Heaps**
19. **Graphs**
20. **System Design (Bonus)**

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
