# Suffix Array and LCP Array

This folder contains C++ implementations of:
- **Suffix Array** (Prefix Doubling method)
- **LCP Array** (Kasai's Algorithm)

---

## ✅ Problem Solved

- Construct the **suffix array** for a string: Sorted list of all suffixes’ starting indices.
- Construct the **LCP array**: Longest Common Prefix between consecutive suffixes in the suffix array.

---

## 🧠 Why This Is Important

- Core data structures in **string algorithms**
- Used in **pattern matching**, **text indexing**, **compression algorithms (e.g., BWT)**, and **bioinformatics**

---

## 📥 Sample Input

Enter string:  
**banana**

---

## 📤 Sample Output

Suffix Array:  
6 5 3 1 0 4 2  
  
LCP Array:  
0 1 3 0 0 2

---

## ⏱ Time Complexities

| Algorithm        | Time      |
|------------------|-----------|
| Suffix Array     | O(n log²n) |
| LCP Array (Kasai)| O(n)      |

---

## 📁 Files

- `SuffixArray.cpp`: Builds suffix array using prefix doubling
- `LCPArray.cpp`: Builds LCP array using Kasai’s algorithm
- `README.md`: Problem explanation, use cases, complexity, and references

---

## 📚 References

- [CP Algorithms - Suffix Array](https://cp-algorithms.com/string/suffix-array.html)
- [Kasai’s Algorithm - GeeksforGeeks](https://www.geeksforgeeks.org/lcp-array-using-kasai-algorithm/)

---
