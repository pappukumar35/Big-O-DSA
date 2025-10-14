<!-- ================================================== -->
<h1 align="center">📘 LeetCode Big O Notebook</h1>
<!-- ================================================== -->

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

<p align="center">
  ⭐ If you found this helpful, give it a <b>star</b> on GitHub!  
  <br><br>
  <img src="https://github-readme-stats.vercel.app/api?username=pappukumar35&show_icons=true&theme=tokyonight" width="400"/>
</p>





