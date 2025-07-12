# LinkedIN-Web-Scrappe
LinkedIn Web Scrapper Job Scrapper
# 🔎 LinkedIn Job Scraper

This is a simple Python script to scrape job postings from LinkedIn using unofficial endpoints. It extracts job details like **job title**, **company name**, **posting time**, and **number of applicants**, then saves everything into a structured CSV file.

---

## 📌 What It Does

- Sends HTTP requests to LinkedIn's **guest job listing API**
- Parses job listings from search results
- Fetches **detailed job information** for each job using job IDs
- Outputs the results to a CSV file (`jobs.csv`)

---

## ⚙️ Technologies Used

- `requests` – for sending HTTP requests  
- `BeautifulSoup` – for parsing HTML  
- `pandas` – for structuring and exporting data to CSV  

---

## 🛠️ How to Use

1. **Install dependencies**:

```bash
pip install requests beautifulsoup4 pandas

title = "Your Job Title"
location = "Your Preferred Location"

python linkedin_scraper.py
