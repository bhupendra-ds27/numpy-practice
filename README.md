# 🔢 NumPy — Numerical Computing with Python

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?style=flat&logo=numpy)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00?style=flat&logo=googlecolab)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat)

> A beginner-friendly NumPy notebook covering **arrays, indexing, slicing, broadcasting, matrix operations, and array manipulation** — the foundation of every Data Science and ML project.

---

## 📌 Topics Covered

| # | Topic | Key Functions |
|---|-------|--------------|
| 1 | **Array Creation** | `np.array()`, `np.arange()`, `np.zeros()`, `np.ones()`, `np.linspace()` |
| 2 | **Random Generation** | `np.random.rand()`, `np.random.randn()`, `np.random.randint()` |
| 3 | **Array Attributes** | `.shape`, `.size`, `.dtype` |
| 4 | **Array Methods** | `.min()`, `.max()`, `.sum()`, `.mean()`, `.std()`, `.argmax()`, `.argmin()` |
| 5 | **Reshape & Resize** | `.reshape()` |
| 6 | **Indexing & Slicing** | 1D vectors, 2D matrices, specific elements |
| 7 | **Boolean Indexing** | Filter arrays using conditions |
| 8 | **Arithmetic Operations** | `+`, `-`, `*`, `/`, `//` on arrays |
| 9 | **Broadcasting** | Scalar & matrix operations without loops |
| 10 | **Deep vs Shallow Copy** | Understanding memory references in NumPy |
| 11 | **Matrix Operations** | `@` (dot product), `.T` (transpose) |
| 12 | **Array Manipulation** | `np.vstack()`, `np.hstack()`, `np.column_stack()`, `np.hsplit()`, `np.vsplit()` |

---

## ✨ Key Concepts Explained

### 🔹 Array Creation
```python
arr = np.array([1, 2, 3, 4])           # from list
arr = np.arange(1, 11, 2)              # range with step
arr = np.zeros((6, 6))                 # all zeros
arr = np.linspace(0, 1, 100)           # 100 evenly spaced values
```

### 🔹 Indexing & Slicing
```python
arr[6]            # single element
arr[1:5]          # slice
arr[3::2]         # step slicing
arr[0:2, 1:3]     # 2D matrix slice
arr[:, 2]         # entire column
```

### 🔹 Boolean Indexing
```python
bool_index = arr % 2 == 0   # condition
arr[bool_index]              # filter even numbers
```

### 🔹 Broadcasting
```python
arr + 10          # add 10 to every element (no loop needed!)
arr2 + 10         # works on 2D arrays too
```

### 🔹 Matrix Operations
```python
A @ B    # matrix multiplication (dot product)
A.T      # transpose of matrix
```

### 🔹 Stack & Split
```python
np.vstack((a, b))       # vertical stack
np.hstack((a, b))       # horizontal stack
np.hsplit(c, 2)         # split horizontally
np.vsplit(c, 4)         # split vertically
```

---

## 💡 Why NumPy?

| Without NumPy | With NumPy |
|---------------|------------|
| Use loops for math | Vectorized operations (much faster) |
| Slow on large data | Optimized C-based backend |
| Manual reshaping logic | `.reshape()` in one line |
| Complex matrix math | `@` operator and `.T` |

NumPy is the backbone of **Pandas, Matplotlib, Scikit-learn, TensorFlow** — learning it is essential for any Data Science journey.

---

## 🛠️ Tech Stack

- **Python 3**
- **NumPy** — Core numerical computing library
- **Google Colab** — Development environment

---

## 🚀 How to Run

### Option 1 — Google Colab (Recommended)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bhupendra-ds27/numpy-practice/blob/main/NUMPY.ipynb)

### Option 2 — Run Locally
```bash
# Clone the repo
git clone https://github.com/bhupendra-ds27/numpy-practice.git
cd numpy-practice

# Install dependencies
pip install numpy

# Open the notebook
jupyter notebook NUMPY.ipynb
```

---

## 📁 Repository Structure

```
numpy-practice/
│
├── NUMPY.ipynb      # Main notebook with all examples
└── README.md        # Project documentation
```

---

## 🗺️ Learning Path

This notebook is part of my **Data Science learning journey**:

```
NumPy  →  Pandas  →  Matplotlib  →  Scikit-learn  →  ML Projects
  ✅           ⬜           ✅              ⬜               ⬜
```

---

## 🎯 Who is this for?

- 🐣 **Beginners** starting their Data Science journey
- 📚 **Students** learning Python for ML/AI
- 💼 Anyone building their **Data Science portfolio**

---

## 👨‍💻 Author

**Bhupendra** — [@bhupendra-ds27](https://github.com/bhupendra-ds27)

---

⭐ **If this helped you, please star the repo!** It motivates me to keep learning and sharing.
