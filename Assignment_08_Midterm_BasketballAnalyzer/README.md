# Midterm Project: Basketball Data Analyzer

This midterm project provides an interactive analytical platform to evaluate professional basketball performance and efficiency across global leagues (NBA, Euroleague) for the seasons 1999–2019. The application calculates custom Analytical Efficiency Ratings, generates Top 10 leaderboards, displays standardized player profiles, and executes side-by-side Head-to-Head performance delta comparisons.

---

## Technical Stack & Environment

* **Language:** Python 3+
* **Libraries:** Pandas, Pathlib, IPython
* **Environment:** Jupyter Notebook (`.ipynb`)
* **Reference Curriculum:** CIS 2266 / Python for Data Analysis / Midterm Comprehensive Project

---

## Repository Structure

```text
Assignment_08_Midterm_BasketballAnalyzer/
├── docs/
│   └── Assignment_08_Midterm_BasketballAnalyzer.pdf    # Exported project documentation
├── notebooks/
│   ├── Assignment_08_Midterm_BasketballAnalyzer.ipynb  # Executed analytical engine notebook
│   └── players_stats_by_season_full_details.csv        # Comprehensive multi-league dataset
└── README.md
```

---

## Workflow & Core Concepts

* **Data Ingestion & Schema Validation:**  
  Validated CSV structures, normalized column headers to uppercase, and filtered seasonal datasets by performance stage (`REGULAR_SEASON`, `INTERNATIONAL`).

* **Analytical Efficiency Engine:**  
  Implemented custom mathematical formulas to evaluate player impact based on points, rebounds, assists, missed field goals, and turnovers:
  $$\text{Efficiency} = (\text{PTS} + \text{REB} + \text{AST}) - (\text{FGA} - \text{FGM}) - \text{TOV}$$

* **Interactive CLI & Sub-Menu Controllers:**  
  Designed robust input validation loops with dynamic suggestions, case-insensitive string matching, and seamless navigation controls (`BACK`, `EXIT`).

* **Dynamic Text-Based Reporting & UI Layouts:**  
  Constructed symmetrical player report cards, ranked leaderboards, and comparative duel tables with real-time delta calculations and automated winner determination.

---

## How to Run

1. Open **Anaconda Prompt** (or your standard terminal/Command Prompt).

2. Navigate to the project directory:
   ```bash
   jupyter notebook
   ```

4. Launch Jupyter Notebook:
   ```bash
   cd python_data_analytics_intro/Assignment_08_Midterm_BasketballAnalyzer
   ```

5. In the browser window that opens automatically, navigate to the `notebooks/` folder and open `Assignment\_08\_Midterm\_BasketballAnalyzer.ipynb`.

6. Run all cells sequentially from top to bottom to initialize the application and interact with the main menu.
