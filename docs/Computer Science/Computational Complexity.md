## Computational Complexity

### Introduction
Computational complexity refers to the quantitative measure used to describe the amount of computational time and resources consumed by an algorithm. The two primary forms of complexity are time complexity and space complexity.

### Time Complexity

#### Definition
- Time complexity represents the amount of time an algorithm takes to run as a function of the length of the input.
  
#### Big O Notation
- The most common notation to represent time complexity is the Big O notation. It describes the upper bound of an algorithm's running time.
- Examples include \(O(1)\), \(O(N)\), \(O(\log N)\), \(O(N^2)\), \(O(N \log N)\), etc.

#### Time Complexities Overview:
- **Constant Time: \(O(1)\)**
  - The algorithm takes a constant amount of time, irrespective of the input size.
  
- **Logarithmic Time: \(O(\log N)\)**
  - The algorithm takes time proportional to the logarithm of the input size.
  
- **Linear Time: \(O(N)\)**
  - The algorithm's runtime increases linearly with the input size.

- **Linear Logarithmic Time: \(O(N \log N)\)**
  - Common in algorithms that divide the input in each step, like many sorting algorithms.

- **Polynomial Time: \(O(N^k)\)**
  - Where \(k\) is a constant. Polynomial-time algorithms become impractical for large inputs.
  
- **Exponential Time: \(O(2^N)\), \(O(k^N)\)**
  - The algorithm's runtime doubles with each additional element in the input. These algorithms are often impractical for even small inputs.

### Space Complexity

#### Definition
- Space complexity represents the amount of memory space an algorithm takes relative to the input size.

#### Big O Notation for Space
- Similar to time complexity, space complexity is often expressed using Big O notation, like \(O(1)\), \(O(N)\), \(O(N^2)\), etc.

#### Space Complexities Overview:
- **Constant Space: \(O(1)\)**
  - The algorithm uses a fixed amount of space.
  
- **Linear Space: \(O(N)\)**
  - The algorithm's space requirement grows linearly with the input size.

### Complexity Classes
- **P-Class:**
  - Algorithms that can be solved in polynomial time.

- **NP-Class:**
  - Non-deterministic Polynomial time. Problems where a solution, once guessed, can be verified quickly.

- **NP-Complete:**
  - The hardest problems in NP-class, to which all NP problems can be reduced.

- **NP-Hard:**
  - Problems that are at least as hard as the hardest problems in NP-class.

### Conclusion
Understanding computational complexity is crucial for designing efficient algorithms and systems. Time and space complexities provide a high-level understanding of an algorithm’s efficiency and help developers make informed choices about which algorithms to use under different circumstances.