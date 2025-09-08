# Google Index Checker

A Python tool to check if a list of URLs is **indexed on Google** using the **Google Custom Search API**.  
Results are exported into an Excel file with structured columns.

---

## 🚀 Features
- Reads URLs from a `sites.txt` file  
- Checks if each URL is indexed on Google  
- Outputs results into `output.xlsx` with two columns:  
  - **Site** (URL)  
  - **Status** (`Indexed` / `Not Indexed`)  

---

## 📦 Requirements
- Python 3.8+  
- Google Cloud Project with **Custom Search API** enabled  
- A **Custom Search Engine (CSE)** set to search the entire web  

Install Python dependencies:
```bash
pip install requests openpyxl
