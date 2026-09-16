\# Assignment 03: Conditionals and Pay Calculation



This assignment covers Python conditional execution (`if-elif-else` statements), error handling with `try-except` blocks, and logical branching based on the course curriculum requirements. The project implements a score-to-grade evaluation tool and an advanced payroll calculator incorporating overtime logic.



\---



\## Technical Stack \& Environment



\* \*\*Language:\*\* Python 3+

\* \*\*Environment:\*\* Jupyter Notebook (`.ipynb`)

\* \*\*Reference Curriculum:\*\* CIS 2260 / Python for Data Analysis / Conditionals



\---



\## Repository Structure



```text

Assignment\_03\_Conditionals/

├── docs/

│   └── Assignment\_03\_Conditionals.pdf      # Exported worksheet report

├── notebooks/

│   └── Assignment\_03\_Conditionals.ipynb    # Executed analysis notebook

└── README.md



\## Workflow \& Core Concepts



\* \*\*Conditional Branching \& Score Evaluation:\*\*  

&#x20; Created a function to evaluate numeric scores between 0.0 and 1.0, translating them into corresponding letter grades (`A` through `F`) using structured `if-elif-else` logic.



\* \*\*Error Handling \& Input Validation:\*\*  

&#x20; Implemented `try-except` blocks to gracefully catch invalid non-numeric inputs and validate that scores fall within the acceptable boundary range.



\* \*\*Overtime Payroll Calculation:\*\*  

&#x20; Developed an extended gross pay script that automatically calculates regular wages for up to 40 hours and applies a time-and-a-half (1.5x) overtime rate for any hours worked beyond the 40-hour threshold.



\---



\## How to Run



1\. Open \*\*Anaconda Prompt\*\* (or your standard terminal/Command Prompt).



2\. Navigate to the assignment directory:

&#x20;  ```bash

&#x20;  cd python\_data\_analytics\_intro/Assignment\_03\_Conditionals



3\. Launch Jupyter Notebook:

&#x20;  ```bash

&#x20;  jupyter notebook



4\. In the browser window that opens automatically, navigate to the notebooks/ folder and open Assignment\_03\_Conditionals.ipynb.



5\. Run all cells sequentially to test the conditional grading logic and overtime payroll calculations.





