\# Assignment 04: File Processing \& Data Extraction



This assignment focuses on file handling and text parsing in Python based on data analytics curriculum requirements. The program reads through structured text files, searches for specific target patterns (`X-DSPAM-Confidence`), extracts floating-point values, and computes statistical summaries such as total count and mean confidence.



\---



\## Technical Stack \& Environment



\* \*\*Language:\*\* Python 3+

\* \*\*Environment:\*\* Python Script / Jupyter Environment

\* \*\*Reference Curriculum:\*\* CIS 2260 / Python for Data Analysis / Files \& Strings



\---



\## Repository Structure



```text

Assignment\_04\_Files/

├── docs/

│   └── Assignment\_04\_Files.pdf             # Exported assignment documentation

├── notebooks/

│   └── mbox-short.txt                      # Source dataset for text parsing

└── README.md



\---



\## Workflow \& Core Concepts



\* \*\*File System Operations:\*\*  

&#x20; Utilized the `pathlib` module to check for file existence and safely open external text documents using UTF-8 encoding.



\* \*\*Text Parsing \& Filtering:\*\*  

&#x20; Iterated through the file line-by-line, identifying lines starting with specific target phrases (`X-DSPAM-Confidence`) and parsing numeric metrics.



\* \*\*Statistical Aggregation:\*\*  

&#x20; Accumulated totals, counted matching lines, and computed the average confidence score, outputting formatted results.



\---



\## How to Run



1\. Open \*\*Anaconda Prompt\*\* (or your standard terminal/Command Prompt).



2\. Navigate to the assignment directory:

&#x20;  ```bash

&#x20;  cd python\_data\_analytics\_intro/Assignment\_04\_Files



3\. Run the processing script to execute file parsing operations against mbox-short.txt

