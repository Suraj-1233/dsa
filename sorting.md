# 🌟 Sorting Algorithms Detailed Summary

## ✅ 1️⃣ Bubble Sort

### 💡 Working

Repeatedly compare adjacent elements and swap if they are in the wrong order. After each pass, the largest element "bubbles" to the end.

### ⚡ Time Complexity

* Best: O(n)
* Average: O(n²)
* Worst: O(n²)

### 🗂️ Space Complexity

* O(1)

### ✅ Advantages

* Simple to understand
* Detects if already sorted

### ❌ Disadvantages

* Very slow on large datasets

### 💬 When to use?

* Small or nearly sorted arrays

---

## ✅ 2️⃣ Selection Sort

### 💡 Working

Find the minimum element and put it in its correct position in each iteration.

### ⚡ Time Complexity

* Best: O(n²)
* Average: O(n²)
* Worst: O(n²)

### 🗂️ Space Complexity

* O(1)

### ✅ Advantages

* Minimum number of swaps

### ❌ Disadvantages

* Always O(n²), even if already sorted

### 💬 When to use?

* When memory writes are costly

---

## ✅ 3️⃣ Insertion Sort

### 💡 Working

Start from the second element and insert each element into its correct position in the sorted left part.

### ⚡ Time Complexity

* Best: O(n)
* Average: O(n²)
* Worst: O(n²)

### 🗂️ Space Complexity

* O(1)

### ✅ Advantages

* Simple and efficient for small or nearly sorted arrays
* Stable

### ❌ Disadvantages

* Inefficient on large datasets

### 💬 When to use?

* Small datasets or almost sorted arrays

---

## ✅ 4️⃣ Merge Sort

### 💡 Working

Divide the array into halves recursively, then merge the sorted halves.

### ⚡ Time Complexity

* Best: O(n log n)
* Average: O(n log n)
* Worst: O(n log n)

### 🗂️ Space Complexity

* O(n)

### ✅ Advantages

* Guaranteed O(n log n)
* Stable

### ❌ Disadvantages

* Uses extra space

### 💬 When to use?

* When stability is required and performance guarantee is important

---

## ✅ 5️⃣ Quick Sort

### 💡 Working

Pick a pivot, partition elements into smaller and greater than pivot, and recursively sort partitions.

### ⚡ Time Complexity

* Best: O(n log n)
* Average: O(n log n)
* Worst: O(n²)

### 🗂️ Space Complexity

* O(log n)

### ✅ Advantages

* Fast on average
* In-place

### ❌ Disadvantages

* Not stable
* Worst-case O(n²)

### 💬 When to use?

* Large datasets when average performance is more important than worst case

---

## ✅ 6️⃣ Heap Sort

### 💡 Working

Build a max heap, repeatedly remove the root (max), place at the end.

### ⚡ Time Complexity

* Best: O(n log n)
* Average: O(n log n)
* Worst: O(n log n)

### 🗂️ Space Complexity

* O(1)

### ✅ Advantages

* In-place
* No extra memory needed

### ❌ Disadvantages

* Not stable
* Often slower in practice compared to Quick Sort

### 💬 When to use?

* When constant extra space is required, and stability isn’t needed

---

# 🎯 Quick Summary Table

| Algorithm      | Best       | Average    | Worst      | Space    | Stable | When to Use                    |
| -------------- | ---------- | ---------- | ---------- | -------- | ------ | ------------------------------ |
| Bubble Sort    | O(n)       | O(n²)      | O(n²)      | O(1)     | ✅ Yes  | Very small or nearly sorted    |
| Selection Sort | O(n²)      | O(n²)      | O(n²)      | O(1)     | ❌ No   | When minimum swaps needed      |
| Insertion Sort | O(n)       | O(n²)      | O(n²)      | O(1)     | ✅ Yes  | Small or nearly sorted arrays  |
| Merge Sort     | O(n log n) | O(n log n) | O(n log n) | O(n)     | ✅ Yes  | Stability & guaranteed perf.   |
| Quick Sort     | O(n log n) | O(n log n) | O(n²)      | O(log n) | ❌ No   | Large datasets, fast avg perf. |
| Heap Sort      | O(n log n) | O(n log n) | O(n log n) | O(1)     | ❌ No   | When minimal space needed      |

---

## ✅ Easy Reminder Tips

* **Bubble:** Big bubbles go to the end.
* **Selection:** Select the smallest repeatedly.
* **Insertion:** Insert into sorted left part.
* **Merge:** Divide and merge.
* **Quick:** Pivot and partition.
* **Heap:** Heapify and remove root.

---

🎁 *Feel free to copy this into your README.md directly!*
