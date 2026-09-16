# Assignment 11: Exploratory Data Analysis & Iris Visualization

This assignment covers exploratory data analysis and multidimensional data visualization using Python statistical plotting libraries based on course requirements. The project loads and validates the classic Iris dataset, verifies structural integrity, generates categorical scatter plots for sepal and petal dimensions grouped by species, constructs feature pairplots, and computes a correlation matrix heatmap.

---

## Technical Stack & Environment

* **Language:** Python 3+
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook (`.ipynb`)
* **Reference Curriculum:** CIS 2266 / Python for Data Analysis / Iris Category Exercise

---

## Repository Structure

```text
Assignment_11_IrisAnalysis/
├── docs/
│   └── Assignment_11_IrisAnalysis.pdf      # Exported assignment documentation
├── notebooks/
│   ├── Assignment_11_IrisAnalysis.ipynb    # Executed analysis and visualization notebook
│   └── iris.csv                            # Source Iris feature dataset
└── README.md
```

---

## Workflow & Core Concepts

* **Data Loading & Integrity Verification:**  
  Imported tabular features from `iris.csv`, evaluated descriptive summary statistics, checked for missing values, and confirmed balanced class distributions across all three species.

* **Categorical Scatter Plotting (Sepal & Petal Dimensions):**  
  Created scatter plots mapping sepal length versus sepal width as well as petal length versus petal width, differentiated by distinct color palettes for `setosa`, `versicolor`, and `virginica`.

* **Multivariate Pairwise Analysis:**  
  Utilized Seaborn pairplots to visualize all possible feature combinations simultaneously alongside univariate kernel density distributions.

* **Correlation Matrix Heatmap:**  
  Computed pairwise Pearson correlation coefficients across physical attributes and rendered annotated heatmaps to identify mathematical relationships between floral dimensions.

---

## How to Run

1. Open **Anaconda Prompt** (or your standard terminal/Command Prompt).

2. Ensure `iris.csv` is located inside the `notebooks/` directory.

3. Navigate to the assignment directory:
   ```bash
   cd python_data_analytics_intro/Assignment_11_IrisAnalysis
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. In the browser window that opens automatically, navigate to the `notebooks/` folder and open `Assignment\_11\_IrisAnalysis.ipynb`.


6. Run all cells sequentially to execute the data pipeline and generate analytical summary plots.
