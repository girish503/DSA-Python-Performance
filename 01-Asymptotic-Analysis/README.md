# 📉 Asymptotic Analysis & Performance Benchmarks
**The Engineering standard for predictable and scalable code.**

### ⚖️ Time Complexity (Execution Speed)
In this repository, we prioritize the hierarchy of efficiency to ensure software reliability:

| Notation | Name | Speed | Real-world Context |
| :--- | :--- | :--- | :--- |
| **$O(1)$** | Constant | Instant | Accessing an array index or dictionary key. |
| **$O(\log n)$** | Logarithmic | Very Fast | Binary search or Digit extraction. |
| **$O(n)$** | Linear | Fair | Iterating through a single list. |
| **$O(n \log n)$**| Linearithmic | Good | Industry-standard sorting (Merge Sort). |
| **$O(n^2)$** | Quadratic | Slow | Nested loops — Risky for $N > 10^4$. |



### 💾 Space Complexity (Memory Footprint)
We distinguish between the data provided and the memory our logic consumes:
* **Input Space:** The memory taken by the initial data (e.g., $N$ integers in a list).
* **Auxiliary Space:** The **extra** memory our algorithm creates. We aim for **$O(1)$** whenever possible to keep the memory footprint low.

### 🛡️ The $10^8$ Rule (The Physics of Code)
Modern CPUs handle roughly **$10^8$ operations per second**.
* If $N = 10^5$, an $O(n^2)$ algorithm requires $10^{10}$ operations.
* Result: **100 seconds execution time** (Guaranteed TLE Error).
