# Gatorade Restaurant

A clean, beautiful single-page restaurant website built with Flask and deployed on Vercel.

## Features
- Hero section with restaurant branding
- About section
- Menu section with 6 items
- Contact section

## Local Development

### Prerequisites
- Python 3.9+

### Setup

```bash
git clone <your-repo-url>
cd gatorade-restaurant
pip install -r requirements.txt
python api/index.py
```

Visit `http://localhost:5000` in your browser.

## Deploy to Vercel

```bash
npm install -g vercel
vercel
```

Follow the prompts. Vercel will auto-detect the configuration from `vercel.json`.

## Project Structure

```
gatorade-restaurant/
├── api/
│   └── index.py        # Flask app entry point
├── templates/
│   └── index.html      # Single page HTML template
├── static/
│   └── style.css       # Styles
├── requirements.txt
├── vercel.json
└── README.md
```
