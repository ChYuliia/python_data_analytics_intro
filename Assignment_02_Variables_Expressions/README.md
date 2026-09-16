# Assignment 02: Variables, Expressions, and Statements

This assignment covers foundational Python programming concepts, including user input handling, type conversion (`float()`), arithmetic expressions, formatted strings (`f-strings`), and variable assignment based on course curriculum requirements. The program computes gross pay using dynamic user prompts and test benchmarks.

---

## Technical Stack & Environment

* **Language:** Python 3+
* **Environment:** Jupyter Notebook (`.ipynb`)
* **Reference Curriculum:** CIS 2266 / Python for Data Analysis / Programming Logic

---

## Repository Structure

```text
Assignment_02_Variables_Expressions/
├── docs/
│   └── Assignment_02_Variables_Expressions.pdf      # Exported worksheet report
├── notebooks/
│   └── Assignment_02_Variables_Expressions.ipynb    # Executed analysis notebook
└── README.md

```

---

## Workflow & Core Concepts

* **User Input & Type Casting:**  
  Utilized the `input()` function to capture string values from the user and converted them into numeric floats using `float()`.

* **Arithmetic Operations & Formatting:**  
  Computed gross pay by multiplying hours worked by the hourly rate, formatting the final monetary output to two decimal places using Python f-strings.

* **Testing & Validation:**  
  Tested the implementation using standard benchmark inputs (35 hours at $2.75 per hour) yielding the correct expected output of $96.25.

---

How to Run

1. Open Anaconda Prompt (or your standard terminal/Command Prompt).

2. Navigate to the assignment directory:

     ```Bash
     cd python_data_analytics_intro/Assignment_02_Variables_Expressions
     ```
	
3. Launch Jupyter Notebook:
     ```Bash
     jupyter notebook
     ```
5. In the browser window that opens automatically, navigate to the `notebooks/` folder and open `Assignment_02_Variables_Expressions.ipynb`.

6. Run all cells sequentially to execute the interactive prompts and view calculations.
