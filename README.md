# AMAZON-WEB-SCRAPPER
A web scraper to track Amazon product prices using Python
# 📦 Amazon Web Scraper

## 📖 Overview

This project is a **Python-based web scraper** that extracts product details (price, title, and availability) from **Amazon** using `BeautifulSoup` and `requests`. It can be used to track price changes and send email alerts when the price drops below a set threshold.

## 🛠️ Features

- Scrapes **Amazon product details** (title, price, and availability)
- Stores the data in a **CSV file**
- Sends **email notifications** when the price drops below a desired amount
- Can be scheduled to run at regular intervals using **cron jobs (Linux/macOS) or Task Scheduler (Windows)**

## 🏗️ Tech Stack

- **Python** (Core Programming Language)
- **BeautifulSoup** (HTML Parsing)
- **Requests** (Fetching Web Pages)
- **Pandas** (Data Storage & Analysis)
- **Smtplib** (Email Notifications)

## 🔧 Installation

### Prerequisites

Make sure you have **Python 3.x** installed. You can check by running:

```bash
python --version
```

### Clone the Repository

```bash
git clone https://github.com/your-username/Amazon-Web-Scraper.git
cd Amazon-Web-Scraper
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## 🚀 Usage

1. **Update **`` with your Amazon product URL and desired price threshold.
2. Run the scraper:
   ```bash
   python scraper.py
   ```
3. If the price is below the threshold, an **email notification** will be sent.

## 📝 Example Output

```plaintext
Product: Apple AirPods Pro
Current Price: $199.99
Desired Price: $180.00
Status: Price is still high. No email sent.
``
