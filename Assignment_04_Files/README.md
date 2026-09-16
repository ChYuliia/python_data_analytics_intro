# Assignment 04: File Processing & Data Extraction

This assignment focuses on file handling and text parsing in Python based on data analytics curriculum requirements. The program reads through structured text files, searches for specific target patterns (`X-DSPAM-Confidence`), extracts floating-point values, and computes statistical summaries such as total count and mean confidence.

---

## Technical Stack & Environment

* **Language:** Python 3+
* **Environment:** Python Script / Jupyter Environment
* **Reference Curriculum:** CIS 2266 / Python for Data Analysis / Files & Strings

---

## Repository Structure

```text
Assignment_04_Files/
├── docs/
│   └── Assignment_04_Files.pdf             # Exported assignment documentation
├── notebooks/
│   ├── Assignment_04_Files.ipynb           # Executed analysis notebook
│   └── mbox-short.txt                      # Source dataset for text parsing
└── README.md
```

---

## Workflow & Core Concepts

* **File System Operations:**  
  Utilized the `pathlib` module to check for file existence and safely open external text documents using UTF-8 encoding.

* **Text Parsing & Filtering:**  
  Iterated through the file line-by-line, identifying lines starting with specific target phrases (`X-DSPAM-Confidence`) and parsing numeric metrics.

* **Statistical Aggregation:**  
  Accumulated totals, counted matching lines, and computed the average confidence score, outputting formatted results.

---

## How to Run

1. Open **Anaconda Prompt** (or your standard terminal/Command Prompt).

2. Navigate to the assignment directory:
   ```bash
   cd python_data_analytics_intro/Assignment_04_Files
   ```
   
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   
4. In the browser window that opens automatically, navigate to the `notebooks/` folder and open the assignment notebook.

5. Run all cells sequentially to execute file parsing operations against `mbox-short.txt`.
