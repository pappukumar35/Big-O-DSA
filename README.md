<!-- ================================================== -->
<h1 align="center">📘 LeetCode Big O Notebook</h1>
<!-- ================================================== ---->

<p align="center">
  <img src="https://media.giphy.com/media/3o7TKCjz1V3r0u32Ji/giphy.gif" width="200"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Algorithm-Analysis-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/DSA-Time_Complexity-brightgreen?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LeetCode-Notebook-orange?style=for-the-badge"/>
</p>

<p align="center">
  🚀 Master <b>Big O Notation</b> with this interactive-style notebook built for 
  <b>DSA, LeetCode, and Interview Preparation</b>!  
</p>

---

## ⚡ 1️⃣ Big O Notation — The Foundation

> 🧠 **Big O** tells how your algorithm’s runtime grows as input size increases.  

| Complexity | Name | Example |
|-------------|------|----------|
| 🟩 `O(1)` | Constant | Access array element |
| 🟦 `O(log n)` | Logarithmic | Binary Search |
| 🟨 `O(n)` | Linear | Traverse array |
| 🟧 `O(n log n)` | Linearithmic | Merge Sort |
| 🟥 `O(n²)` | Quadratic | Bubble Sort |
| 🔺 `O(2ⁿ)` | Exponential | Recursive Fibonacci |
| 🔻 `O(n!)` | Factorial | Traveling Salesman Problem |

🎯 **Quick Insight:**  
- `O(1)` → Fastest 💨  
- `O(n!)` → Slowest 🐢  

---

## 🧰 2️⃣ Data Structures Complexity Table

| Data Structure | Access | Search | Insertion | Deletion |
|----------------|---------|---------|------------|-----------|
| 🧱 Array | O(1) | O(n) | O(n) | O(n) |
| 🔗 Linked List | O(n) | O(n) | O(1) | O(1) |
| 🧮 Stack | O(n) | O(n) | O(1) | O(1) |
| 🌀 Queue | O(n) | O(n) | O(1) | O(1) |
| ⚡ Hash Table | O(1) | O(1) | O(1) | O(1) |
| 🌳 Binary Search Tree | O(log n) | O(log n) | O(log n) | O(log n) |
| 🏔 Heap | O(n) | O(n) | O(log n) | O(log n) |

🪄 **Tip:** Hash Tables and Heaps are kings in performance for insert/delete!

---

## 🧩 3️⃣ Algorithm Complexity Summary

### Sorting Algorithms

| Algorithm | Best | Average | Worst | Space |
|------------|-------|----------|--------|--------|
| 🫧 Bubble Sort | O(n) | O(n²) | O(n²) | O(1) |
| ✂️ Selection Sort | O(n²) | O(n²) | O(n²) | O(1) |
| 📥 Insertion Sort | O(n) | O(n²) | O(n²) | O(1) |
| 🔀 Merge Sort | O(n log n) | O(n log n) | O(n log n) | O(n) |
| ⚡ Quick Sort | O(n log n) | O(n log n) | O(n²) | O(log n) |
| 🧱 Heap Sort | O(n log n) | O(n log n) | O(n log n) | O(1) |

### Search Algorithms

| Algorithm | Time Complexity |
|------------|----------------|
| 🔎 Linear Search | O(n) |
| 📈 Binary Search | O(log n) |

### Graph Algorithms

| Algorithm | Time Complexity |
|------------|----------------|
| 🔄 BFS / DFS | O(V + E) |
| 🚦 Dijkstra | O(E log V) |
| 🌐 Floyd Warshall | O(V³) |

---

## 🧮 4️⃣ Recursion & Master Theorem
📘 **Master Theorem Formula:**




Where:  
- `a` = number of subproblems  
- `n/b` = size of each subproblem  
- `f(n)` = cost outside recursive calls  

| Case | Condition | Complexity |
|------|------------|-------------|
| Case 1 | f(n) < n^(log_b a) | O(n^(log_b a)) |
| Case 2 | f(n) = n^(log_b a) | O(n^(log_b a) log n) |
| Case 3 | f(n) > n^(log_b a) | O(f(n)) |

✨ Example:  
`T(n) = 2T(n/2) + O(n)` → **O(n log n)**  

🧩 **Growth Order Comparison:**



---

## 💾 5️⃣ Space Complexity Insights

| Operation | Space | Example |
|------------|--------|----------|
| Iterative Loop | O(1) | Counting |
| Recursion | O(n) | Factorial |
| DP Memoization | O(n²) | LCS Problem |

🧩 **Stack Memory in Recursion:**  
Each call adds a new frame → grows linearly with recursion depth.

---

## 🧠 6️⃣ LeetCode Patterns with Big O

| Pattern | Example | Time |
|----------|----------|-------|
| 🎯 Two Pointer | Two Sum II | O(n) |
| 🔍 Sliding Window | Longest Substring Without Repeating | O(n) |
| 🧮 Binary Search on Answer | Koko Eating Bananas | O(log n) |
| 🧵 Dynamic Programming | Climbing Stairs | O(n) |
| ♟️ Backtracking | N-Queens | O(N!) |

🧠 *Learn patterns, not problems.*

---

## 📈 7️⃣ Big O Growth Visualization




🌱 Small Input → All seem fine  
🔥 Large Input → Only efficient algorithms survive!

---

## 📦 8️⃣ Resources

📚 **Best Learning Links:**
- 🔗 [LeetCode Patterns](https://leetcode.com/problemset/all/)
- 🧾 [Big O Cheat Sheet](https://github.com/ericdrowell/BigOCheatSheet)
- 📘 [Master Theorem - GFG](https://www.geeksforgeeks.org/analysis-of-algorithms-set-4-master-method/)
- 🎥 [Visual Algorithms - Visualgo.net](https://visualgo.net/en)

---

## 👨‍💻 Author

**Pappu Kumar**  
💼 Java Backend Developer | ☕ Spring Boot | 🧩 DSA Enthusiast  

📧 [tpgcoder@gmail.com](mailto:tpgcoder@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/pappukumar35) • [GitHub](https://github.com/pappukumar35)

---





  <!-- ================================================== -->
<h1 align="center">📘 LeetCode Big O Notebook — Practice Questions</h1>
<!-- ================================================== -->



# ⚡ 1️⃣ Big O Notation — The Foundation (20 Questions)

1. What is the time complexity of accessing an array element?  
2. Compare O(n log n) vs O(n²) — which grows faster for n=1000?  
3. Give an example of an O(1) operation in Java.  
4. What is the Big O of nested loops (two for-loops)?  
5. Which algorithm has O(log n) time complexity?  
6. How do you calculate the time complexity of a function?  
7. What’s the difference between O(n) and O(n+100)?  
8. Explain amortized O(1) complexity with an example.  
9. Which is faster — O(n log n) or O(2ⁿ)?  
10. What’s the time complexity of checking if a number exists in a sorted array using binary search?  
11. Define asymptotic analysis.  
12. What’s the worst-case complexity of QuickSort?  
13. What’s the space complexity of an iterative Fibonacci algorithm?  
14. What does Big Ω (Omega) represent?  
15. What is the difference between O, Ω, and Θ notations?  
16. Which is more efficient: O(n²) or O(n log n)? Why?  
17. When does Big O ignore constants?  
18. What is the complexity of a three-level nested loop?  
19. Why is O(1) considered constant time even if it takes 10 operations?  
20. How can you estimate Big O from code without executing it?

---

# 🧰 2️⃣ Data Structures Complexity (20 Questions)

1. What is the access time complexity of an array?  
2. Why is searching in a linked list O(n)?  
3. How is a stack implemented using arrays?  
4. What is the average time complexity of searching in a hash table?  
5. What is the worst-case complexity of inserting in a hash table?  
6. Why is deletion in a stack O(1)?  
7. What is the time complexity of inserting at the end of a linked list?  
8. Compare ArrayList vs LinkedList insertion complexity in Java.  
9. What is the access complexity of a heap’s top element?  
10. Why are trees faster than linked lists for searching?  
11. What is the complexity of building a Binary Search Tree from n elements?  
12. What’s the complexity of deleting a node in a heap?  
13. How does hash collision affect performance?  
14. Which data structure offers average O(1) lookup?  
15. What is the space complexity of a stack with n elements?  
16. Compare time complexity of queue enqueue vs dequeue.  
17. What’s the complexity of reversing a linked list?  
18. What’s the difference between AVL tree and normal BST in terms of complexity?  
19. How does resizing affect array complexity?  
20. What data structure gives best insertion/deletion performance?

---

# 🧩 3️⃣ Algorithm Complexity (Sorting & Searching) (20 Questions)

1. What’s the best-case complexity of Bubble Sort?  
2. Which sorting algorithm is stable and has O(n log n) complexity?  
3. Why is Merge Sort preferred over QuickSort in some cases?  
4. What is the worst-case of QuickSort and why?  
5. What’s the difference between Merge Sort and Heap Sort in space usage?  
6. Which sort algorithm performs best on nearly-sorted data?  
7. Write the recurrence relation of Merge Sort.  
8. What is the complexity of Selection Sort?  
9. Why is Bubble Sort rarely used in practice?  
10. Which algorithm is O(log n) and used for searching?  
11. What’s the complexity of Binary Search Tree traversal?  
12. Compare the space complexity of Merge Sort vs Quick Sort.  
13. What’s the average complexity of Quick Sort?  
14. What’s the complexity of counting sort?  
15. How does Radix Sort differ from comparison-based sorts?  
16. Which sorting method is best for small datasets?  
17. What’s the worst-case time for Insertion Sort?  
18. What’s the time complexity of Linear Search?  
19. Why does Binary Search require sorted input?  
20. Which algorithm gives O(n log n) performance consistently?

---

# 🧮 4️⃣ Recursion & Master Theorem (20 Questions)

1. Define recursion in algorithms.  
2. What is the recurrence relation for binary search?  
3. How does recursion affect space complexity?  
4. Derive time complexity of Merge Sort using the Master Theorem.  
5. What is “a”, “b”, and “f(n)” in T(n) = aT(n/b) + f(n)?  
6. What case of Master Theorem applies to Merge Sort?  
7. What is the complexity of T(n) = T(n/2) + O(1)?  
8. What’s the base case in recursion?  
9. Why can recursion cause stack overflow?  
10. What’s the time complexity of recursive Fibonacci?  
11. How can recursion be converted into iteration?  
12. What’s the time complexity of T(n) = 3T(n/2) + O(n)?  
13. What is the difference between tail and non-tail recursion?  
14. When does recursion outperform iteration?  
15. What is memoization in recursion?  
16. What’s the time complexity of a recursive binary tree traversal?  
17. Which case of Master Theorem gives O(n log n)?  
18. Why is recursion slower than iteration sometimes?  
19. What’s the space complexity of recursion with depth n?  
20. Explain Master Theorem Case 3 with an example.

---

# 💾 5️⃣ Space Complexity Insights (20 Questions)

1. Define space complexity.  
2. What’s the space complexity of iterative factorial?  
3. How much space does recursion consume?  
4. What is auxiliary space?  
5. Compare stack vs heap memory usage.  
6. What’s the space complexity of merge sort?  
7. How can we optimize space in dynamic programming?  
8. What’s the space complexity of BFS using a queue?  
9. What is memoization space used for?  
10. What’s the space complexity of storing a 2D array (n×n)?  
11. What’s the space complexity of DFS using recursion?  
12. Can an algorithm have O(1) space and O(n²) time?  
13. What is the difference between total and auxiliary space?  
14. What’s the impact of recursion depth on stack size?  
15. How can space complexity be reduced in recursive Fibonacci?  
16. What’s the space complexity of a hash map with n entries?  
17. What’s the space complexity of quicksort (recursive)?  
18. Why does dynamic programming often use more space?  
19. What’s the difference between in-place and out-of-place algorithms?  
20. How do you estimate total memory used by a program?

---

# 🧠 6️⃣ LeetCode Patterns with Big O (20 Questions)

1. What is the Two Pointer technique used for?  
2. What’s the time complexity of the Sliding Window approach?  
3. Which pattern is used in “Container With Most Water”?  
4. What’s the space complexity of Dynamic Programming solutions?  
5. Which pattern does the “N-Queens” problem use?  
6. What’s the time complexity of BFS/DFS traversal in graphs?  
7. Which pattern is used for problems like “Three Sum”?  
8. What is Binary Search on Answer pattern?  
9. What’s the Big O of “Climbing Stairs” (DP)?  
10. Which pattern applies to “Longest Substring Without Repeating”?  
11. What’s the complexity of recursive backtracking problems?  
12. Why are patterns more important than problems in LeetCode?  
13. Which pattern fits “Koko Eating Bananas”?  
14. What’s the complexity of Kadane’s Algorithm?  
15. Which pattern is useful for “Merge Intervals”?  
16. What’s the complexity of two-pointer palindrome checking?  
17. What’s the space complexity of memoized recursion?  
18. Which problems use binary search + greedy combo?  
19. What’s the complexity of DFS with visited set?  
20. How does recognizing patterns help in interviews?

---

# 📈 7️⃣ Big O Growth Visualization (20 Questions)

1. Plot O(n) vs O(n²) — which grows faster?  
2. What happens to O(n³) as n → 1000?  
3. How does input size affect exponential algorithms?  
4. Why is Big O important for scalability?  
5. How does algorithm growth relate to performance?  
6. Which complexity curve flattens quickest?  
7. Compare growth of O(log n) vs O(n log n).  
8. How does constant factor affect growth rate?  
9. What’s the effect of doubling input size in O(n²)?  
10. Which complexity remains nearly flat as n increases?  
11. What’s the “break-even point” between O(n log n) and O(n²)?  
12. Why are exponential algorithms impractical for large n?  
13. Which complexity curve is steepest?  
14. How can visualization help in algorithm selection?  
15. What’s the significance of asymptotic behavior?  
16. Which grows faster — O(2ⁿ) or O(n!)?  
17. How can you approximate performance using graphs?  
18. How does logarithmic complexity look on graph?  
19. What is the shape of linear vs quadratic growth?  
20. Why do efficient algorithms matter for large datasets?

---

# 📦 8️⃣ Resources (20 Questions)

1. What is the Big O Cheat Sheet used for?  
2. Which site helps visualize algorithms interactively?  
3. What is the best platform to practice DSA problems?  
4. Which site provides animated data structure operations?  
5. Where can you find Master Theorem explanation?  
6. What’s the best way to learn time complexity — code or visualize?  
7. Which GitHub repo summarizes DSA complexities?  
8. What resource teaches pattern-based problem solving?  
9. What’s the best YouTube channel for visual algorithms?  
10. How can LeetCode Patterns help interview prep?  
11. Which platform provides company-wise DSA questions?  
12. How to track time/space complexity during coding?  
13. Which website allows comparing algorithms side-by-side?  
14. Where can you find detailed explanations of Big O proofs?  
15. What’s a good way to memorize complexities?  
16. Which GFG topic should you read for recurrence relations?  
17. Where can you practice Master Theorem problems?  
18. Which visual tool helps see recursion in action?  
19. How can GitHub be used to document your DSA learning?  
20. Why is building your own Big O Notebook beneficial?

---

## 👨‍💻 Author

**Pappu Kumar**  
💼 Java Backend Developer | ☕ Spring Boot | 🧩 DSA Enthusiast  

📧 [tpgcoder@gmail.com](mailto:tpgcoder@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/pappukumar35) • [GitHub](https://github.com/pappukumar35)

---

<p align="center">
  ⭐ If you found this helpful, give it a <b>star</b> on GitHub!  
  <br><br>
  <img src="https://github-readme-stats.vercel.app/api?username=pappukumar35&show_icons=true&theme=tokyonight" width="400"/>
</p>

</p>





