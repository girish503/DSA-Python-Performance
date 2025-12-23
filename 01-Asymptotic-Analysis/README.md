# 📈 01. Asymptotic Analysis (Big O)

### 💡 The Philosophy
In engineering, "fast" is not enough. We need "Scalable." Asymptotic Analysis is the language we use to describe how our algorithms perform as data grows from 10 elements to 10 Billion elements.

### 🚀 The "Girish" Standard: The 10^8 Rule
I build all my solutions based on the **10^8 Operations per Second** rule. If an algorithm exceeds this limit for the given constraints, it is not "production-ready."

### ⚖️ Complexity Benchmarks
I categorize my solutions into these primary efficiency tiers:

1. **O(1) - Constant Time:** Operations that take the same time regardless of input size (e.g., Mathematical formulas like `math.log10`).
2. **O(log N) - Logarithmic Time:** High-efficiency logic where the problem size is reduced by a factor in each step (e.g., Digit Extraction, Binary Search).
3. **O(sqrt N) - Square Root Time:** Optimized search logic (e.g., Finding Factors/Primes).
4. **O(N) - Linear Time:** Looking at every element exactly once (e.g., Linear Search).
5. **O(N log N) - Linear-Logarithmic:** The gold standard for sorting.

---

### 🛠️ Technical Lessons Learned
* **Time Complexity:** Measuring the growth of operations.
* **Space Complexity:** Measuring the Auxiliary Space (extra RAM) used by the algorithm.
* **Optimization Goal:** Always aim for $O(1)$ Auxiliary Space whenever possible to minimize Cloud/Server costs.
