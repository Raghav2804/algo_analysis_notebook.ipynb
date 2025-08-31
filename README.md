Algorithm Efficiency Analysis Project
📌 Introduction

This project is a practical implementation for analyzing and comparing the time complexity and space complexity of different algorithms. The objective is to study how algorithms behave under different input sizes and to visualize their efficiency using Python.

The project covers:

Sorting algorithms (Comparison of different strategies)

Fibonacci sequence (Naïve recursion vs Dynamic Programming)

Binary Search (efficient searching technique)

By running experiments and generating graphs, we can clearly see the trade-offs between different algorithms in terms of execution time and memory usage.

🧮 Algorithms Implemented
1. Sorting Algorithms

Bubble Sort – Simple, but inefficient for large data (O(n²)).

Insertion Sort – Good for nearly sorted data (O(n²) worst case).

Selection Sort – Performs selection in every pass (O(n²)).

Merge Sort – Divide & conquer, efficient (O(n log n)).

Quick Sort – Fast on average (O(n log n)), but worst-case O(n²).

2. Fibonacci Sequence

Naïve Recursive Approach – Exponential growth in time (O(2ⁿ)).

Dynamic Programming Approach – Uses memoization/iteration, much faster (O(n)).

3. Search Algorithm

Binary Search – Works on sorted lists, reduces search space by half each step (O(log n)).

⚙️ Methodology

Implemented algorithms in Python.

Measured performance using:

Execution Time (in seconds)

Memory Usage (in MiB)

Conducted experiments with increasing input sizes.

Visualized results using Matplotlib graphs.

📈 Graphs & Results

Sorting Algorithm Performance (Execution Time)

Merge Sort and Quick Sort perform significantly better than Bubble, Insertion, and Selection Sort as input size grows.

Sorting Algorithm Memory Usage

Memory usage remains almost constant across sorting algorithms, but recursive ones (Merge/Quick) use slightly more stack memory.

Fibonacci Naïve vs DP

Naïve recursion grows very slow beyond n=30 due to exponential time.

DP version is efficient and handles very large inputs easily.

Fibonacci DP Performance

Execution time increases linearly with n.

Memory usage is stable and minimal.

🛠️ Tools & Libraries Used

Python 3

NumPy – Array operations

Matplotlib – Data visualization

psutil & memory_profiler – Performance measurement

🚀 How to Run

Install required libraries:

// pip install numpy matplotlib psutil memory_profiler


Open the notebook in Jupyter or Google Colab.

Run cells to generate results and plots.

📊 Key Insights

Quadratic algorithms (Bubble, Insertion, Selection) are only practical for small input sizes.

Divide and Conquer algorithms (Merge, Quick) scale much better.

Dynamic Programming transforms exponential problems into polynomial ones.

Measuring both time and memory provides a complete understanding of efficiency.

✨ Conclusion

This project demonstrates that algorithm choice is critical. For real-world large datasets, efficient algorithms like Merge Sort, Quick Sort, and DP approaches outperform naïve methods drastically.

This aligns with the Design and Analysis of Algorithms (DAA) course objective:

To evaluate algorithms not only for correctness but also for efficiency.
