# URL Shortener

A simple web app that takes long URLs and turns them into short, shareable links.

---

## What it does

- Paste a long URL, get a short one back
- Short link redirects you to the original URL
- Tracks how many times each link was clicked
- Clean and minimal interface

---

## Tech Stack

- Python + Flask — backend and routing
- SQLAlchemy — database management
- SQLite — stores the URLs
- HTML + CSS + Jinja2 — frontend templates

---

## How to Run
```
git clone https://github.com/vortellex/shortener.git
cd shortener
pip install -r requirements.txt
python app.py
```

Then open `http://localhost:5000` in your browser.

---

## How it works

1. User submits a long URL
2. App generates a unique short code
3. Short code and original URL are saved to the database
4. When someone visits the short link, app looks up the code and redirects them

---

## Author

**Shubham Kumar Gupta**  
github.com/vortellex
