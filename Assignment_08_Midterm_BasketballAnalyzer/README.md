\# Midterm Project: Basketball Data Analyzer



This midterm project provides an interactive analytical platform to evaluate professional basketball performance and efficiency across global leagues (NBA, Euroleague) for the seasons 1999–2019. The application calculates custom Analytical Efficiency Ratings, generates Top 10 leaderboards, displays standardized player profiles, and executes side-by-side Head-to-Head performance delta comparisons.



\---



\## Technical Stack \& Environment



\* \*\*Language:\*\* Python 3+

\* \*\*Libraries:\*\* Pandas, Pathlib, IPython

\* \*\*Environment:\*\* Jupyter Notebook (`.ipynb`)

\* \*\*Reference Curriculum:\*\* CIS 2260 / Python for Data Analysis / Midterm Comprehensive Project



\---



\## Repository Structure



```text

Assignment\_08\_Midterm\_BasketballAnalyzer/

├── docs/

│   └── Assignment\_08\_Midterm\_BasketballAnalyzer.pdf    # Exported project documentation

├── notebooks/

│   ├── Assignment\_08\_Midterm\_BasketballAnalyzer.ipynb  # Executed analytical engine notebook

│   └── players\_stats\_by\_season\_full\_details.csv        # Comprehensive multi-league dataset

└── README.md



\---



\## Workflow \& Core Concepts



\* \*\*Data Ingestion \& Schema Validation:\*\*  

&#x20; Validated CSV structures, normalized column headers to uppercase, and filtered seasonal datasets by performance stage (`REGULAR\_SEASON`, `INTERNATIONAL`).



\* \*\*Analytical Efficiency Engine:\*\*  

&#x20; Implemented custom mathematical formulas to evaluate player impact based on points, rebounds, assists, missed field goals, and turnovers:

&#x20; $$\\text{Efficiency} = (\\text{PTS} + \\text{REB} + \\text{AST}) - (\\text{FGA} - \\text{FGM}) - \\text{TOV}$$



\* \*\*Interactive CLI \& Sub-Menu Controllers:\*\*  

&#x20; Designed robust input validation loops with dynamic suggestions, case-insensitive string matching, and seamless navigation controls (`BACK`, `EXIT`).



\* \*\*Dynamic Text-Based Reporting \& UI Layouts:\*\*  

&#x20; Constructed symmetrical player report cards, ranked leaderboards, and comparative duel tables with real-time delta calculations and automated winner determination.



\---



\## How to Run



1\. Open \*\*Anaconda Prompt\*\* (or your standard terminal/Command Prompt).



2\. Ensure `players\_stats\_by\_season\_full\_details.csv` is located inside the `notebooks/` directory.



3\. Navigate to the assignment directory:

&#x20;  ```bash

&#x20;  cd python\_data\_analytics\_intro/Assignment\_08\_Midterm\_BasketballAnalyzer



4\. Launch Jupyter Notebook:

&#x20;  ```bash

&#x20;  jupyter notebook



5\. In the browser window that opens automatically, navigate to the notebooks/ folder and open Assignment\_08\_Midterm\_BasketballAnalyzer.ipynb.



6\. Run all cells sequentially from top to bottom to initialize the application and interact with the main menu.

