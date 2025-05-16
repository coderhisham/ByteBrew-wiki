
Analyzing algorithms is essential for understanding how efficiently they solve problems, especially as the size of input data grows. The two primary aspects of algorithm analysis are **time complexity** and **space complexity**.

## **Time Complexity**

**Definition:**  
Time complexity is a fundamental concept in analyzing algorithms, describing how the running time of an algorithm increases with the size of the input. To express this growth, we use [[Asymptotic Notations]] primarily Big O, Big Omega (Ω), and Big Theta (Θ). Each provides a different perspective on an algorithm's performance as input size grows large.

**Key Points:**

- **Big O Notation:** Time complexity is usually expressed in Big O notation, which describes the upper bound of the running time in the worst-case scenario (e.g., O(1), O(n), O(log⁡n), O(n^2)).

- **Types of Time Complexity:**
    - **Constant Time (O(1))**: Execution time does not depend on input size.
    - **Linear Time (O(n))**: Execution time increases linearly with input size.
    - **Logarithmic Time (O(log⁡n))**: Execution time increases logarithmically (e.g., binary search).
    - **Quadratic Time (O(n2))**: Execution time increases quadratically (e.g., nested loops).
    - **Exponential Time (O(2n))**: Execution time doubles with each addition to input size.
- **Best, Average, and Worst Case:** Time complexity can be analyzed for best, average, or worst-case scenarios, but worst-case is most commonly used.
- **Practical Impact:** Algorithms with lower time complexity are generally preferred for large datasets, as they are more scalable and efficient.