\# Assignment 12: Iris Data Analysis Part 2 (Correlation \& Distribution Study)



This assignment covers advanced correlation studies and distribution analysis on the classic Iris dataset based on course requirements. The project implements species-grouped Pearson correlation computations for sepal versus petal dimensions, linear regression trendlines, and customized frequency histograms illustrating sepal length distributions across floral species.



\---



\## Technical Stack \& Environment



\* \*\*Language:\*\* Python 3+

\* \*\*Libraries:\*\* Pandas, NumPy, Matplotlib

\* \*\*Environment:\*\* Jupyter Notebook (`.ipynb`)

\* \*\*Reference Curriculum:\*\* CIS 2266 / Python for Data Analysis / Iris Data Analysis Part 2



\---



\## Repository Structure



```text

Assignment\_12\_IrisAnalysis\_Part2/

├── docs/

│   └── Assignment\_12\_IrisAnalysis\_Part2.pdf # Exported assignment documentation

├── notebooks/

│   ├── Assignment\_12\_IrisAnalysis\_Part2.ipynb # Executed analysis notebook

│   └── iris.csv                            # Source Iris feature dataset

└── README.md



\---



\## Workflow \& Core Concepts



\* \*\*Grouped Correlation Analysis:\*\*  

&#x20; Computed intra-species Pearson correlation coefficients between sepal width and petal width, as well as sepal length and petal length, using Pandas groupby and correlation routines.



\* \*\*Linear Regression \& Scatter Visualization:\*\*  

&#x20; Generated colored scatter plots paired with least-squares polynomial fit lines (`np.polyfit`) to visualize structural relationships and variance across `setosa`, `versicolor`, and `virginica`.



\* \*\*Distribution Histograms:\*\*  

&#x20; Constructed transparent overlapping frequency histograms (`plt.hist`) to analyze and compare sepal length dispersion patterns among the three species.



\* \*\*Hypothesis \& Assumption Validation:\*\*  

&#x20; Tested biological growth assumptions, confirming that length parameters exhibit stronger linear dependency than width parameters, and that \*Iris setosa\* presents unique outlier behaviors relative to the other two species.



\---



\## How to Run



1\. Open \*\*Anaconda Prompt\*\* (or your standard terminal/Command Prompt).



2\. Ensure `iris.csv` is located inside the `notebooks/` directory.



3\. Navigate to the assignment directory:

&#x20;  ```bash

&#x20;  cd python\_data\_analytics\_intro/Assignment\_12\_IrisAnalysis\_Part2



4\. Launch Jupyter Notebook:

Bash



jupyter notebook



5\. In the browser window that opens automatically, navigate to the notebooks/ folder and open Assignment\_12\_IrisAnalysis\_Part2.ipynb.



6\. Run all cells sequentially to execute the correlation models and generate distribution plots.

