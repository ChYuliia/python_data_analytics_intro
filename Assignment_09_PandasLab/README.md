# Assignment 09: Pandas Lab & Integrated Visualization

This assignment covers foundational and intermediate data manipulation techniques using Pandas alongside integrated plotting routines. The project implements DataFrame creation, structural inspection, filtering with boolean indexing, group-by aggregations, missing value handling, and statistical visualization including bar plots, stacked plots, histograms, scatter plots, and box plots.

---

## Technical Stack & Environment

* **Language:** Python 3+
* **Libraries:** Pandas, NumPy, Matplotlib
* **Environment:** Jupyter Notebook (`.ipynb`)
* **Reference Curriculum:** CIS 2266 / Python for Data Analysis / Pandas Lab v3

---

## Repository Structure

```text
Assignment_09_PandasLab/
├── docs/
│   └── Assignment_09_PandasLab.pdf         # Exported assignment documentation
├── notebooks/
│   └── Assignment_09_PandasLab.ipynb       # Executed analysis notebook
└── README.md
```

---

## Workflow & Core Concepts

* **DataFrame Fundamentals & Inspection:**  
  Constructed indexed DataFrames from dictionaries, generated statistical summaries using `.describe()`, and evaluated dataset metadata and structural types.

* **Data Selection & Boolean Filtering:**  
  Extracted specific subsets of data based on column headers, row counts, visit frequencies, missing values (`NaN`), and multi-condition criteria.

* **Aggregation & Grouping:**  
  Performed group-wise metric calculations (such as mean age per animal category) and value frequency counts.

* **Integrated Data Visualization:**  
  Leveraged Pandas built-in plot wrappers to generate customized bar charts, stacked multi-series bar plots, frequency histograms, relationship scatter plots, and distribution box plots.

---

## How to Run

1. Open **Anaconda Prompt** (or your standard terminal/Command Prompt).

2. Navigate to the assignment directory:
   ```bash
   cd python_data_analytics_intro/Assignment_09_PandasLab
   ```


3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. In the browser window that opens automatically, navigate to the `notebooks/` folder and open `Assignment\_09\_PandasLab.ipynb`.

5. Run all cells sequentially to execute data manipulation commands and render visualizations.
