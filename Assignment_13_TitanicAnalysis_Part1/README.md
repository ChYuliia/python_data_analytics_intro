\# Assignment 13: Titanic Exploratory Data Analysis (Part 1)



This assignment covers exploratory data analysis (EDA) on the Titanic passenger dataset based on course requirements. The project implements data inspection, missing value verification, statistical summaries, age-versus-fare scatter plots, child survival probability calculations for third-class passengers, ticket price distribution histograms, and class-stratified fare boxplots.



\---



\## Technical Stack \& Environment



\* \*\*Language:\*\* Python 3+

\* \*\*Libraries:\*\* Pandas, NumPy, Matplotlib

\* \*\*Environment:\*\* Jupyter Notebook (`.ipynb`)

\* \*\*Reference Curriculum:\*\* CIS 2266 / Python for Data Analysis / Titanic Data Analysis Project (Part 1)



\---



\## Repository Structure



```text

Assignment\_13\_TitanicAnalysis\_Part1/

├── docs/

│   └── Assignment\_13\_TitanicAnalysis\_Part1.pdf # Exported assignment documentation

├── notebooks/

│   ├── Assignment\_13\_TitanicAnalysis\_Part1.ipynb # Executed analysis notebook

│   └── titanic.csv                         # Source Titanic passenger dataset

└── README.md



\---



\## Workflow \& Core Concepts



\* \*\*Exploratory Data Inspection:\*\*  

&#x20; Loaded passenger records from `titanic.csv`, verified data types and completeness via `.info()` and `.isnull().sum()`, and generated numerical statistical overviews (`.describe()`).



\* \*\*Vulnerability \& Class Survival Analysis:\*\*  

&#x20; Filtered passenger subsets using boolean indexing to calculate the precise survival probability for children aged 10 or younger traveling in Third Class (41.51%).



\* \*\*Financial \& Fare Stratification:\*\*  

&#x20; Analyzed overall average ticket pricing (£32.31) alongside minimum and maximum fare extremes across passenger classes (Pclass 1–3), identifying luxury outliers and complementary zero-fare tickets.



\* \*\*Advanced Statistical Visualization:\*\*  

&#x20; Constructed multi-variable age-vs-fare scatter plots annotated by survival status, age distribution histograms highlighting youth vulnerability, and class-based boxplots illustrating economic disparity.



\---



\## How to Run



1\. Open \*\*Anaconda Prompt\*\* (or your standard terminal/Command Prompt).



2\. Ensure `titanic.csv` is located inside the `notebooks/` directory.



3\. Navigate to the assignment directory:

&#x20;  ```bash

&#x20;  cd python\_data\_analytics\_intro/Assignment\_13\_TitanicAnalysis\_Part1



4\. Launch Jupyter Notebook:

Bash



jupyter notebook



5\. In the browser window that opens automatically, navigate to the notebooks/ folder and open Assignment\_13\_TitanicAnalysis\_Part1.ipynb.



6\. Run all cells sequentially to execute the data pipeline and render visual reports.

