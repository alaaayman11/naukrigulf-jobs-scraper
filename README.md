# Naukrigulf Data Engineer Jobs Scraper 🚀

A Python-based Web Scraping automation project using **Selenium** to extract Data Engineer job opportunities from **Naukrigulf**, iterate through multiple pages, and export the structured data to a CSV file.

## 📌 Project Overview
The objective of this assignment is to automatically scrape job details from Naukrigulf for "Data Engineer" roles across multiple pagination pages.

### 🎯 Extracted Attributes:
- **Job Title**
- **Company Name**
- **Job Location**
- **Required Experience**
- **Full Job Description**

---

## 🛠️ Technologies & Libraries Used
- **Python 3.x**
- **Selenium WebDriver** (for automated Web Navigation)
- **Pandas** (for Data Wrangling & CSV Export)
- **Time** (for timing & delays)

---

## 📂 Project Structure
- `APT1.ipynb`: Jupyter Notebook containing the Python code for scraping.
- `naukrigulf_jobs.csv`: The generated dataset containing all scraped job listings.

---

## ⚙️ How It Works
1. Initializes Chrome WebDriver and navigates to the target search URL on Naukrigulf.
2. Scrolls down to ensure dynamically loaded elements are rendered correctly.
3. Uses robust XPATH strategies and fallback `try-except` structures to handle missing data smoothly.
4. Iterates across pages using dynamic direct page navigation.
5. Converts collected job dictionaries into a Pandas DataFrame and exports it to a UTF-8 encoded CSV file.
