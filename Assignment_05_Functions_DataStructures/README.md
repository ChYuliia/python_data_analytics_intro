\# Assignment 05: Functions, Lists, and Dictionaries



This assignment covers advanced foundational Python concepts based on the course curriculum requirements. It implements modular computation using user-defined functions, text tokenization and alphabetical sorting via Python lists, and frequency analysis of email senders using dictionaries.



\---



\## Technical Stack \& Environment



\* \*\*Language:\*\* Python 3+

\* \*\*Environment:\*\* Python Script / Jupyter Environment

\* \*\*Reference Curriculum:\*\* CIS 2260 / Python for Data Analysis / Functions, Lists, Dictionaries



\---



\## Repository Structure



```text

Assignment\_05\_Functions\_DataStructures/

├── docs/

│   └── Assignment\_05\_Functions\_DataStructures.pdf  # Exported assignment documentation

├── notebooks/

│   ├── romeo.txt                                   # Source text for list processing

│   └── mbox-short.txt                              # Source dataset for dictionary analysis

└── README.md



\---



\## Workflow \& Core Concepts



\* \*\*Modular Functions \& Overtime Pay:\*\*  

&#x20; Created a reusable `computepay` function to calculate standard wages and time-and-a-half (1.5x) overtime compensation for hours exceeding the 40-hour threshold.



\* \*\*List Processing \& Text Sorting:\*\*  

&#x20; Read through `romeo.txt` line by line, split text into words, removed duplicates, and sorted the resulting collection alphabetically.



\* \*\*Dictionary Aggregation \& Frequency Tracking:\*\*  

&#x20; Parsed `mbox-short.txt` to identify sender addresses from `From` lines, mapping them into a dictionary to determine the most active contributor.



\---



\## How to Run



1\. Open \*\*Anaconda Prompt\*\* (or your standard terminal/Command Prompt).



2\. Navigate to the assignment directory:

&#x20;  ```bash

&#x20;  cd python\_data\_analytics\_intro/Assignment\_05\_Functions\_DataStructures



3\. Run the processing scripts to execute function logic, list manipulations, and dictionary aggregations against the provided text files.

