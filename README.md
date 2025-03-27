# Linkedin-Job-Scraper-Using-Web-Scraping
# **LinkedIn Job Scraper**

## 📌 **Project Overview**
This project is a web scraper that extracts job listings from LinkedIn using **Requests** and **BeautifulSoup**. The scraped job data is saved in both **CSV** and **SQLite database** for further analysis.

## 🔍 **Insights & Findings**
- Scraped job listings include **Job Title, Company Name, Location, and Job Link**.
- The data can be **filtered and analyzed** to identify hiring trends.
- Storing jobs in **SQLite** allows easy querying and future expansion.
- Automating the scraper can help track **new job postings** over time.

## 🛠 **Tools Used**
- **Python** – Programming language
- **Requests** – For sending HTTP requests
- **BeautifulSoup** – For parsing HTML data
- **Pandas** – For handling and saving job data
- **SQLite** – For storing job listings in a database

## 🚀 **Steps to Perform Scraping**
1. Send an **HTTP request** to LinkedIn Jobs using **Requests**.
2. Parse the HTML content with **BeautifulSoup**.
3. Extract key details: **Job Title, Company, Location, and Job Link**.
4. Save extracted data to a **CSV file**.
5. Store job listings in an **SQLite database**.
6. Retrieve and display job listings from the database.

## 🔗 **Future Scope**
🔹 Automate daily scraping using **Schedule** or **Cron Jobs**  
🔹 Expand to scrape **Indeed & Glassdoor**  
🔹 Create a **Streamlit Dashboard** to display jobs interactively  
🔹 Implement **job alerts via email or Telegram**  

## 📄 **Example Job Data Output**
| Job Title | Company | Location | Job Link |
|-----------|---------|----------|----------|
| Data Analyst | Google | India | [View Job](https://www.linkedin.com/jobs/view/123456) |
| Business Analyst | Microsoft | USA | [View Job](https://www.linkedin.com/jobs/view/654321) |

## 🎯 **Conclusion**
This **LinkedIn Job Scraper** helps job seekers and researchers extract and store job postings for analysis. By automating the process and expanding to multiple job platforms, it can become a powerful tool for tracking job market trends.
