# 🏨 Paris Hotels Web Scraping (TripAdvisor)

This project scrapes hotel listings from **TripAdvisor** for the city of **Paris**, including key details like name, rating, price, and number of reviews. The scraped data can be used for travel planning, analysis, or price trend monitoring.

---

## 🌐 Source Website

- **Website:** [TripAdvisor - Hotels in Paris](https://www.tripadvisor.com/)
- **Target:** Hotel listings in Paris, France

---

## 📦 Features

- Scrapes hotel names, prices, ratings, and review counts
- Handles pagination to collect data across multiple pages
- Saves data to a structured **CSV file** for analysis
- Includes user-agent rotation and delay to prevent blocking

---

## 🧠 Tech Stack

- Python 3.10+
- `requests` – for sending HTTP requests
- `BeautifulSoup` – for HTML parsing
- `pandas` – for data storage/export
- `time` & `random` – for delay/randomness between requests

---

## 🗂️ Output Sample

| Hotel Name            | Rating | Price  | Reviews |
|-----------------------|--------|--------|---------|
| Hôtel Le Six          | 4.5    | $240   | 1,052   |
| Pullman Paris Tour... | 4.0    | $310   | 2,340   |
| Hôtel de Crillon      | 5.0    | $720   | 1,890   |

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/paris-hotels-webscraper.git
   cd paris-hotels-webscraper
