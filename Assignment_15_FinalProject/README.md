# Assignment 15: Final Project - HR Analytics Employee Attrition & Performance

This repository contains the final capstone project for CIS 2266 (Python Data Analytics). The investigation analyzes the IBM HR Analytics dataset to uncover the primary drivers of employee turnover (attrition) and evaluates how financial compensation and demographic life stages moderate workplace stressors.

---

## Technical Stack & Environment

* **Language:** Python 3+
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook (`.ipynb`)
* **Reference Curriculum:** CIS 2266 / Python Data Analytics / Final Capstone Project

---

## Repository Structure

```text
Assignment_15_FinalProject/
├── docs/
│   ├── Data_Analysis_Report.docx             # Detailed analysis report
│   └── Presentation_Yuliia_Chernysheva.pdf   # Project presentation slides
├── notebooks/
│   ├── Employee_Attrition.ipynb              # Executed analysis notebook
│   └── Employee_Attrition.csv                # Source IBM HR Analytics dataset
└── README.md
```

---

## Key Research Questions & Findings

1. **Stress & Income Mitigation (Research Question 1):**  
   Confirmed that while extended work hours (Overtime and Frequent Travel) significantly increase turnover risk, a gross Monthly Income above the **$5,000 threshold** acts as a powerful "Retention Buffer."

2. **Life Stages & Commute Strain (Research Question 2):**  
   Demonstrated that commute distance is heavily moderated by age and marital status. The highest risk concentration (Attrition "Hot Zone") occurs among **young (<30), single employees** with commutes exceeding 10 miles, whereas senior and married employees show high resilience.

---

## Workflow & Core Concepts

* **Data Inspection & Cleaning:**  
  Loaded the IBM HR Analytics dataset (`Employee_Attrition.csv`), verified structural integrity, handled missing values, and prepared categorical features for exploratory data analysis.

* **Stress Factor & Income Mitigation Analysis:**  
  Evaluated the impact of workplace stressors (such as Overtime and Frequent Travel) on employee turnover, demonstrating how a gross Monthly Income above the **$5,000 threshold** acts as an effective retention buffer.

* **Demographic & Life Stage Risk Modeling:**  
  Analyzed commute distance, age, and marital status intersections to identify high-risk demographic clusters (Attrition "Hot Zones"), such as young, single employees with extended commutes.

* **Exploratory Visualization & Reporting:**  
  Generated multi-variable statistical plots and correlation matrices using Seaborn and Matplotlib to synthesize findings into comprehensive reporting documents and presentation slides.

  ---
  
## How to Run

1. Open **Anaconda Prompt** (or your standard terminal/Command Prompt).

2. Ensure `Employee_Attrition.csv` is placed inside the `notebooks/` directory.

3. Navigate to the assignment directory:
   ```bash
   cd python_data_analytics_intro/Assignment_15_FinalProject/notebooks
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. Open 'Employee\_Attrition.ipynb' and run all cells sequentially to execute the complete EDA and reproduce analytical charts.
