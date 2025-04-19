# Mutual Fund NAV Scraper

This project automates the process of extracting mutual fund NAV data from the AMFI India website and storing it in a PostgreSQL database.

## 👨‍💻 Author
GitHub: [Pavan-learn](https://github.com/Pavan-learn)

## ⚙️ Features
- Extracts latest NAV data from AMFI portal
- Parses and inserts data into PostgreSQL
- Modular code with `.env`-based configuration

## 🛡️ Legal & Ethical Note
⚠️ This project is for educational purposes only. The data is fetched from publicly accessible pages on [AMFI India](https://www.amfiindia.com). This repository does not store or redistribute proprietary data. Users are responsible for complying with AMFI's terms of service.

## 📦 Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/Pavan-learn/mutual-fund-nav-scraper.git
cd mutual-fund-nav-scraper
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Configure environment variables:
```bash
cp sample.env .env
# Edit .env to include your PostgreSQL credentials
```

4. Run the notebook using Jupyter.

---
