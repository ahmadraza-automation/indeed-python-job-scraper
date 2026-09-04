# Indeed Python Job Scraper

**Playwright-based scraper** that extracts Python Developer jobs from Indeed and exports them to clean CSV + Excel.

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Playwright](https://img.shields.io/badge/Playwright-Async-green?logo=playwright)](https://playwright.dev/python/)
[![GitHub](https://img.shields.io/badge/GitHub-ahmadraza--automation-181717?logo=github)](https://github.com/ahmadraza-automation)

> **Note:** Indeed frequently changes its HTML and uses anti-bot protection. This project is for educational purposes. Always respect the website’s Terms of Service.

---

### Features

- Async Playwright for reliable browser automation
- Multi-page scraping (configurable)
- Stealth techniques (webdriver flag removed)
- Clean CSV + Excel export
- Duplicate removal by URL

---

### Installation

```bash
pip install -r requirements.txt
playwright install chromium
```

---

### Usage

```bash
python indeed_scraper.py
```

### Configuration

| Setting     | Default | Description                    |
|-------------|---------|--------------------------------|
| `HEADLESS`  | `True`  | Set `False` to see the browser |
| `MAX_PAGES` | `3`     | Number of pages to scrape      |

---

### Output

```
output/
├── indeed_python_jobs.csv
└── indeed_python_jobs.xlsx
```

---

### Author

**Ahmad Raza** — Python Automation Engineer  
[GitHub](https://github.com/ahmadraza-automation) • [Portfolio](https://ahmadraza-automation.github.io/Ahmad-Raza-Automation-Portfolio/)

---

If you find this useful, please give it a ⭐
