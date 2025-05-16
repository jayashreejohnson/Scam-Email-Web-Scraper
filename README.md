# Web Scraping Project – Scam Email Archive Extraction

This project automates the extraction of scam email records from the 419 Scam Email Archive (419scam.org), transforming unstructured HTML into structured, timestamped datasets suitable for analysis or downstream NLP modeling.

---

## 🔍 Implementation

- Crawled the main archive index using `requests` and parsed content with `BeautifulSoup`.
- Filtered archive links by year/month pattern (e.g., `/2023/05/`) and looped through selected archive pages.
- Extracted email link texts, URLs, and derived date metadata from URL structure.
- Applied regex-based filters to remove irrelevant links and noise.
- Compiled clean, structured records into a `pandas` DataFrame and exported to CSV.

---

## ✅ Outcomes

- Created a structured dataset of historical scam emails with timestamps and message links.
- Demonstrated practical web scraping and URL parsing techniques using Python.
- Dataset can be reused for text classification, fraud pattern detection, or cybersecurity research.

---

## 🛠️ Skills Used

**Libraries**: Python, Requests, BeautifulSoup, Regex, Pandas  
**Techniques**: HTML Parsing, URL Pattern Matching, Data Cleaning, Automation

---

## 📁 Files

- `WebScraping.ipynb` – Main scraping script   
- `README.md` – Documentation
