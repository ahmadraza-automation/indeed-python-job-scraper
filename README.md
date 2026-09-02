# Indeed Python Job Scraper

Playwright-based scraper that extracts **Python Developer jobs** from Indeed and exports them to clean CSV + Excel.

**Author:** [Ahmad Raza](https://github.com/ahmadraza-automation)

> **Important:** Indeed frequently changes its HTML structure and uses aggressive anti-bot protection. This project is for educational / personal learning purposes. Always respect Indeed’s Terms of Service and robots.txt.

---

## Features

- Async Playwright for reliable browser automation
- Multi-page scraping (configurable limit)
- Stealth techniques (webdriver flag removed)
- Clean CSV + professionally formatted Excel export
- Duplicate removal by URL

---

## Installation

```bash
pip install -r requirements.txt
playwright install chromium
```

---

## Usage

```bash
python indeed_scraper.py
```

### Configuration (top of script)

| Setting     | Default | Description                    |
|-------------|---------|--------------------------------|
| `HEADLESS`  | `True`  | Set `False` to see the browser |
| `MAX_PAGES` | `3`     | Safety limit on pages          |

---

## Output

```
output/
├── indeed_python_jobs.csv
└── indeed_python_jobs.xlsx
```

---

## Notes

- Selectors may break when Indeed updates their frontend. Update the locator strings in the script if needed.
- For production use consider proxies / residential IPs and slower delays.
- LinkedIn / Indeed style scrapers that require login are intentionally kept simple for safety.

---

## Author

**Ahmad Raza** — Python Automation Engineer  
[GitHub](https://github.com/ahmadraza-automation) · [Portfolio](https://ahmadraza-automation.github.io/Ahmad-Raza-Automation-Portfolio/)
