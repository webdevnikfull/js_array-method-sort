# 🖥️ QA & Algorithms: Custom Implementation of Array.prototype.sort()

> ### A low-level algorithmic project focusing on custom sorting implementation, comparator function contracts, and performance predictability.

This repository demonstrates the ability to implement fundamental data structures and native JavaScript methods from scratch without relying on built-in language abstractions[cite: 4]. 

From a Software Engineering and Quality Assurance perspective, this project showcases deep understanding of algorithmic sorting behavior, edge-case handling, and strict adherence to functional contracts (such as comparator function return values).

---

## 🌐 Live Demo & QA Reports

- **[Live Application Demo](#)** *(Replace with your GitHub Pages demo link if applicable)*
- **[Automated Test HTML Report](#)** *(Replace with your test report link)*

---

## 🧪 QA Focus: Algorithmic Robustness & Edge Cases

Low-level algorithms must handle diverse data types and unexpected inputs without failing. This custom implementation was built keeping strict testing criteria in mind:

### 1. Comparator Function Contract Compliance
Native JavaScript sorting converts elements to strings by default if no comparator is provided, leading to unexpected numeric sorting bugs (e.g., `[10, 2).sort()` returning `[10, 2]`). 
- **QA Advantage:** The custom sort implementation strictly enforces expected sorting contracts, ensuring numbers and strings are handled predictably based on explicit or default comparison rules.

### 2. Immutability vs. In-Place Mutation
While native `Array.prototype.sort()` mutates the original array in place, understanding its side effects is crucial for test isolation. 
- **QA Safeguard:** Unit tests for this task verify that the custom sorting logic correctly handles array indexing, swaps, and boundary constraints without introducing memory leaks or infinite loops.

### 3. Comprehensive Unit Testing
Writing custom sorting algorithms requires validating multiple edge cases:
- Empty arrays and single-element arrays.
- Already sorted vs. reverse-sorted arrays.
- Arrays containing duplicate elements or negative numbers.

---

## 🎯 Technical Specifications (System Under Test)

The custom sorting algorithm addresses the following core requirements:

- **Algorithm Mechanics:** Implements a stable or efficient sorting approach (such as bubble sort, insertion sort, or quicksort logic) tailored to meet the test suite's performance expectations.
- **Comparator Handling:** Accepts an optional comparator function taking two arguments `(a, b)` and respects negative, zero, and positive return values to determine element ordering.
- **Type Safety & Coercion:** Safely handles element type evaluation to ensure consistent comparison outcomes.

---

## 🧰 Tech Stack & Concepts

- **Language:** JavaScript (ES6+)
- **Core Concepts:** Algorithms & Data Structures, Comparator Functions, Time & Space Complexity
- **Testing Approach:** Low-level Unit Testing, Edge-case validation

---

## ⚙️ Local Development

1. Clone the repository:
   ```bash
   git clone [https://github.com/webdevnikfull/js_array-method-sort.git](https://github.com/webdevnikfull/js_array-method-sort.git)
