# Assignment 05: Functions, Lists, and Dictionaries

This assignment covers advanced foundational Python concepts based on the course curriculum requirements. It implements modular computation using user-defined functions, text tokenization and alphabetical sorting via Python lists, and frequency analysis of email senders using dictionaries.

---

## Technical Stack & Environment

* **Language:** Python 3+
* **Environment:** Python Script / Jupyter Environment
* **Reference Curriculum:** CIS 2266 / Python for Data Analysis / Functions, Lists, Dictionaries

---

## Repository Structure

```text
Assignment_05_Functions_DataStructures/
├── docs/
│   └── Assignment_05_Functions_DataStructures.pdf    # Exported assignment documentation
├── notebooks/
│   ├── Assignment_05_Functions_DataStructures.ipynb  # Executed analysis notebook
│   ├── romeo.txt                                     # Source text for list processing
│   └── mbox-short.txt                                # Source dataset for dictionary analysis
└── README.md
```

---

## Workflow & Core Concepts

* **Modular Functions & Overtime Pay:**  
  Created a reusable `computepay` function to calculate standard wages and time-and-a-half (1.5x) overtime compensation for hours exceeding the 40-hour threshold.

* **List Processing & Text Sorting:**  
  Read through `romeo.txt` line by line, split text into words, removed duplicates, and sorted the resulting collection alphabetically.

* **Dictionary Aggregation & Frequency Tracking:**  
  Parsed `mbox-short.txt` to identify sender addresses from `From` lines, mapping them into a dictionary to determine the most active contributor.

---

## How to Run

1. Open **Anaconda Prompt** (or your standard terminal/Command Prompt).

2. Navigate to the assignment directory:
   ```bash
   cd python_data_analytics_intro/Assignment_05_Functions_DataStructures
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   
4. In the browser window that opens automatically, navigate to the `notebooks/` folder and open `Assignment_05_Functions_DataStructures.ipynb`.

5. Run all cells sequentially to execute the modular functions, list sorting operations, and dictionary frequency analysis against `romeo.txt` and `mbox-short.txt`.
