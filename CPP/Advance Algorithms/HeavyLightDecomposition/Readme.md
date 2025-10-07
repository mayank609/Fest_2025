# Heavy Light Decomposition (HLD)

**Heavy Light Decomposition (HLD)** is an advanced technique used to answer tree path queries efficiently. It decomposes a tree into **"heavy" and "light" paths**, allowing us to use a segment tree on top of the decomposition.

---

## ✅ Problem Solved

**Query Maximum Value Between Two Nodes in a Tree**

- You are given a tree with values on nodes.
- Given multiple queries of the form `(u, v)`, return the maximum value on the path between `u` and `v`.

---

## 🧮 Time Complexity

| Operation     | Time     |
|---------------|----------|
| Build         | O(N)     |
| Each Query    | O(log²N) |

---

## 🛠 Techniques Used

- DFS for subtree size and heavy child detection
- HLD for chain decomposition
- Segment Tree for efficient range maximum query

---

## 📥 Input Format (Sample)

Enter number of nodes:  
5  
Enter 4 edges:  
0 1  
1 2  
1 3   
3 4  
Enter values:  
5 2 7 1 3  
Query path max between:  
2 4 


---

## 📤 Output

Maximum value on the path: 7

## 📁 Files

- `HeavyLightDecomposition.cpp` — Complete implementation of HLD with Segment Tree for path maximum queries
- `README.md` — Detailed explanation, I/O, time complexity, and sample

---

## 📚 References

- [CP Algorithms: Heavy Light Decomposition](https://cp-algorithms.com/graph/hld.html)
- [Errichto's Video Explanation](https://www.youtube.com/watch?v=5hPfm_uqXmw)

---

