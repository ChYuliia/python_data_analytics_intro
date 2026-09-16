# Assignment 10: Networked Programs & Web Scraping

This assignment covers networked programming concepts and web scraping techniques based on the course curriculum and textbook references (Chapter 12: Networked Programs). The project implements HTTP requests using the `requests` library and HTML parsing via `BeautifulSoup` to extract and filter URL links from target web pages.

---

## Technical Stack & Environment

* **Language:** Python 3+
* **Libraries:** Requests, BeautifulSoup4
* **Environment:** Jupyter Notebook (`.ipynb`)
* **Reference Curriculum:** CIS 2266 / Python for Data Analysis / Networked Programs & Web Scraping

---

## Repository Structure

```text
Assignment_10_WebScraping/
├── docs/
│   └── Assignment_10_WebScraping.pdf         # Exported assignment documentation
├── notebooks/
│   └── Assignment_10_WebScraping.ipynb       # Executed analysis notebook
└── README.md
```

---

## Workflow & Core Concepts

* **HTTP Request Handling:**  
  Established secure HTTP GET connections with custom user-agent headers and robust error/exception management (`requests.get()` and `raise_for_status()`).

* **HTML Parsing & DOM Traversal:**  
  Parsed raw HTML content using BeautifulSoup with the built-in `html.parser` to navigate and search the document object model.

* **URL Link Extraction & Filtering:**  
  Iterated through anchor (`<a>`) tags with `href` attributes, filtering links matching specific protocol criteria (`http:`) to compile a structured collection of target URLs.

---

## How to Run

1. Open **Anaconda Prompt** (or your standard terminal/Command Prompt).

2. Navigate to the assignment directory:
   ```bash
   cd python_data_analytics_intro/Assignment_10_WebScraping
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. In the browser window that opens automatically, navigate to the `notebooks/` folder and open `Assignment\_10\_WebScraping.ipynb`.

5. Run all cells sequentially to execute live web requests and verify the extracted URL list.
