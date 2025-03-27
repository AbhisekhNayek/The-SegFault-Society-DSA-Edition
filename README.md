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

---

<details>
  <summary>2️⃣ Reverse an Array (Easy)</summary>  

**🔹 Brute Force Approach**  
- Use an extra array to copy elements in reverse order.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

**🔹 Optimal Approach (Two Pointers)**  
- Swap elements from start & end until they meet.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`  

</details>  

---

<details>
  <summary>3️⃣ Move All Zeros to End (Easy)</summary>  

**🔹 Brute Force Approach**  
- Create a new array, add non-zero elements first, then zeros.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

**🔹 Optimal Approach (Two Pointers)**  
- One pointer tracks **non-zero positions**, another iterates.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`  

</details>  

---

<details>
  <summary>4️⃣ Buy & Sell Stock (Single Transaction) (Easy)</summary>  

**🔹 Brute Force Approach**  
- Try all possible `(buy, sell)` pairs and get max profit.  
- **Time Complexity:** `O(N²)`

**🔹 Optimal Approach**  
- Track **minimum price so far** and **max profit** in one pass.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  

---

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

---

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

---

<details>
  <summary>7️⃣ Kadane's Algorithm – Maximum Subarray Sum (Medium)</summary>  

**🔹 Brute Force Approach**  
- Compute sum for all subarrays.  
- **Time Complexity:** `O(N²)`

**🔹 Optimal Approach (Kadane’s Algorithm)**  
- Track `currentSum` and `maxSum`.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  

---

<details>
  <summary>8️⃣ Maximum Product Subarray (Medium)</summary>  

**🔹 Brute Force Approach**  
- Compute product of all subarrays.  
- **Time Complexity:** `O(N²)`

**🔹 Optimal Approach**  
- Track `maxProduct` and `minProduct` dynamically.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(1)`

</details>  

---

<details>
  <summary>9️⃣ Longest Consecutive Sequence (Hard)</summary>  

**🔹 Brute Force Approach**  
- Sort and traverse to count streaks.  
- **Time Complexity:** `O(N log N)`

**🔹 Optimal Approach (Using Set)**  
- Use a HashSet for fast lookup.  
- **Time Complexity:** `O(N)`, **Space Complexity:** `O(N)`

</details>  

---

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

