# MiniProject-Book-Price-Tracker-using-Scrapy 📚

**A B.Tech Minor Project (May–Dec 2025)**  
_Koneru Lakshmaiah University_

---

## 📌 Overview

**Book Price Tracker** is a mini web scraping project designed to extract and monitor book prices from [BooksToScrape.com](http://books.toscrape.com/) using the **Scrapy** framework. The goal is to demonstrate how structured data like prices, ratings, and titles can be programmatically collected and stored for analysis or alerting purposes.

---

## ✨ Features

- Tracks book titles, prices, and star ratings from BooksToScrape  
- Built with **Scrapy**, a powerful Python framework for large-scale scraping  
- Stores data in CSV or JSON format  
- Fast, efficient, and modular architecture  
- Supports pagination for scraping multiple pages  
- Can be deployed as a scheduled scraper for daily/weekly monitoring

---

## 🧠 Problem Statement

Online bookstores frequently update prices, and manually checking them can be time-consuming. This project automates the process of collecting book prices and ratings from a target site. The solution is lightweight, fast, and serves as a base for real-world price tracker applications.

---

## 📊 Performance

- **Pagination Support:** Yes  
- **Speed:** Very fast  
- **Accuracy:** High (XPath and CSS selectors used)  
- **Target Site:** [Books to Scrape](http://books.toscrape.com/)

---

## ⚙️ Tools

1. **Scrapy**  
   - Framework used to crawl and extract data efficiently  
   - Modular spider-based architecture  
   - Fast and scalable

   ![Scrapy Screenshot](https://github.com/user-attachments/assets/408ec426-bfcf-4924-9fe7-09bafd1de9d1)

2. **XPath / CSS Selectors**  
   - Precise extraction of price, title, and star-rating

3. **CSV/JSON Output**  
   - Scraped data saved in structured formats for analysis

---

## 📸 Demonstrations

**Sample Output (Google Colab / Terminal):**

- Extracted titles, prices, and ratings from multiple pages
<img width="1076" height="458" alt="image" src="https://github.com/user-attachments/assets/c7cf32c0-b822-4233-bbc4-8077ee673ab2" />
<img width="1681" height="770" alt="Screenshot 2025-07-19 163652" src="https://github.com/user-attachments/assets/3b090040-1195-4be9-9ccb-f11c4f03c9b1" />


---

## 🛠️ Tech Stack

- **Language**: Python  
- **Framework**: Scrapy  
- **Selectors**: XPath, CSS  
- **Storage**: CSV, JSON  
- **Platform**: Google Colab / Jupyter Notebook / CLI

---

## 💻 How to Run

-bash
# Step 1: Install Scrapy
pip install scrapy

# Step 2: Start a new Scrapy project
scrapy startproject book_tracker

# Step 3: Create a spider
cd book_tracker
scrapy genspider books books.toscrape.com

# Step 4: Run the spider and save output
scrapy crawl books -o output.csv

<h2 id="contact">Contact</h2>
  <p>For any inquiries or feedback, please contact:</p>
  <ul>
    <li><strong>Name:</strong> Ahmadullah Laskar</li>
    <li><strong>Education:</strong> B.tech AI&DS , KLU, Guntur</li>
    <li><strong>Email:</strong> ahmadullahlaskar2004@gmail.com </li>
    <li><strong>GitHub:</strong> <a href="https://github.com/AhmadullahLaskar">Ahmadullah_Laskar</a></li>
  </ul>
  
  
  <h2 id="mentor">Mentor</h2>
  <p><strong>Dr. Sahinur Rahman Laskar</strong><br>
  Assistant Professor<br>
  School of Computer Science, UPES, Dehradun, India<br>
  Email: sahinurlaskar.nits@gmail.com / sahinur.laskar@ddn.upes.ac.in<br>
  </p>


