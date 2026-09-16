# Assignment 06: NumPy Library

This assignment covers foundational and intermediate NumPy library operations based on the course curriculum and textbook references (Chapter 3: The NumPy Library). The project implements multidimensional array generation, slicing, statistical aggregations, reshaping, flat iteration, data type inspection, and file persistence using NumPy.

---

## Technical Stack & Environment

* **Language:** Python 3+
* **Library:** NumPy
* **Environment:** Jupyter Notebook (`.ipynb`)
* **Reference Curriculum:** CIS 2266 / Python for Data Analysis / NumPy Library

---

## Repository Structure

```text
Assignment_06_NumPy/
├── docs/
│   └── Assignment_06_NumPy.pdf             # Exported assignment documentation
├── notebooks/
│   └── Assignment_06_NumPy.ipynb           # Executed analysis notebook
└── README.md
```

---

## Workflow & Core Concepts

* **Array Creation & Random Sampling:**  
  Initialized pseudo-random multidimensional arrays using `np.random.randint()` with fixed seed control for repeatable outputs.

* **Statistical Computations & Slicing:**  
  Extracted specific rows and columns to compute axis-wise descriptive statistics, including mean values for targeted subsets.

* **Shape Manipulation & Iteration:**  
  Converted multidimensional matrices into higher-rank and one-dimensional flat arrays using `.reshape()` and `.flatten()`, utilizing `np.nditer()` for efficient element-wise traversal.

* **File Persistence:**  
  Saved NumPy arrays to disk using binary `.npy` formats and comma-separated `.csv` text outputs.

---

## How to Run

1. Open **Anaconda Prompt** (or your standard terminal/Command Prompt).

2. Navigate to the assignment directory:
   ```bash
   cd python_data_analytics_intro/Assignment_06_NumPy
   ```

3. Launch Jupyter Notebook: 
   ```bash
   jupyter notebook
   ```

4. In the browser window that opens automatically, navigate to the `notebooks/` folder and open `Assignment\_06\_NumPy.ipynb`.

5. Run all cells sequentially to execute NumPy operations and verify array outputs.

