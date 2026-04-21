# 📊 Stream-Scrap — Data Explorer & Weather Scraper

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?style=flat-square&logo=streamlit)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-Scraping-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)

> A Streamlit app combining interactive CSV data exploration with live weather web scraping — built to practice data visualization and BeautifulSoup scraping in a single unified tool.

---

## 📌 What This Project Does

Two tools in one app — upload any CSV for instant visual exploration, or enter any city name to scrape live weather data from the web.

---

## ✨ Features

- 📂 CSV upload with instant data preview
- 📈 Interactive visualizations — Histogram, Box Plot, Scatter Plot
- 🌐 Live weather scraping for any location via BeautifulSoup
- 🧭 Multi-page Streamlit layout

---

## 🛠️ Tech Stack

| Library | Purpose |
|---------|---------|
| Streamlit | UI & multi-page app |
| Pandas | Data handling |
| Matplotlib, Seaborn | Visualizations |
| BeautifulSoup, Requests | Web scraping |

---

## 📂 Project Structure

```
stream-scrap/
├── app.py        # Main Streamlit app
└── README.md
```

---

## 🚀 Setup & Run

```bash
# Clone the repo
git clone https://github.com/AshishChaubey2003/stream--scrap.git
cd stream--scrap

# Install dependencies
pip install streamlit pandas matplotlib seaborn beautifulsoup4 requests

# Run the app
streamlit run app.py
```

---

## 🧪 Usage

1. **Data Upload page** — upload any `.csv` file and preview it
2. **Visualizations tab** — explore data with histogram, boxplot, scatter
3. **Web Scraping page** — enter any city name to get current weather

---

## 🚀 Roadmap

- [ ] Add more chart types — correlation heatmap, line chart
- [ ] Export visualizations as PNG
- [ ] Replace scraping with OpenWeatherMap API for reliability

---

## 📄 License

MIT License — open source and free to use.

---

<p align="center">Built by <a href="https://github.com/AshishChaubey2003">Ashish Kumar Chaubey</a> — B.Tech CSE 2025 | Lucknow, India</p>
<p align="center">
  <a href="https://www.linkedin.com/in/ashishchaubey2dec/">LinkedIn</a> •
  <a href="mailto:sashishchaubey1234@gmail.com">Email</a>
</p>
