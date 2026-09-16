# Assignment 14: Titanic Exploratory Data Analysis (Part 2)

This assignment covers advanced multi-variable exploratory data analysis on the Titanic passenger dataset based on course requirements. The project investigates gender and socio-economic class intersections, calculating exact casualty/survival distributions by sex and ticket class, and computing conditional survival probabilities ($P(\text{Survival} \mid \text{Sex, Class})$).

---

## Technical Stack & Environment

* **Language:** Python 3+
* **Libraries:** Pandas, NumPy, Matplotlib
* **Environment:** Jupyter Notebook (`.ipynb`)
* **Reference Curriculum:** CIS 2266 / Python for Data Analysis / Titanic Data Analysis Project (Part 2)

---

## Repository Structure

```text
Assignment_14_TitanicAnalysis_Part2/
├── docs/
│   └── Assignment_14_TitanicAnalysis_Part2.pdf    # Exported assignment documentation
├── notebooks/
│   ├── Assignment_14_TitanicAnalysis_Part2.ipynb  # Executed analysis notebook
│   └── titanic.csv                                # Source Titanic passenger dataset
└── README.md
```

---

## Workflow & Core Concepts

* **Data Verification & Integrity:**  
  Re-inspected `titanic.csv` to ensure complete records across key categorical and numerical variables without requiring imputation or data cleaning.

* **Gender-Based Survival Distribution:**  
  Grouped passenger records by biological sex to evaluate the massive survival disparity, supporting historical protocols regarding priority evacuation.

* **Socio-Economic Class Stratification:**  
  Aggregated survival outcomes across passenger ticket classes (Pclass 1–3), highlighting how upper-class status drastically increased rescue likelihood.

* **Conditional Probability Analysis:**  
  Computed multi-level grouping metrics to determine precise survival rates across combined demographic segments (e.g., demonstrating that 1st class females experienced a 96.8% survival rate compared to 13.7% for 3rd class males).

---

## How to Run

1. Open **Anaconda Prompt** (or your standard terminal/Command Prompt).

2. Ensure `titanic.csv` is located inside the `notebooks/` directory.

3. Navigate to the assignment directory:
   ```bash
   cd python_data_analytics_intro/Assignment_14_TitanicAnalysis_Part2
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. In the browser window that opens automatically, navigate to the `notebooks/` folder and open `Assignment\_14\_TitanicAnalysis\_Part2.ipynb`.

6. Run all cells sequentially to execute the aggregation pipeline and render visual survival charts.
