# Web Scraping and AI

A collection of modern web scraping techniques and implementations that combine traditional scraping with AI capabilities. The repository showcases different approaches from traditional BeautifulSoup to LLM-powered solutions, with concrete examples, performance metrics, and cost analysis.

## Content

- CODECON 2024 #ZILINA  [Slides](/slides/CODECON%202024%20AI%20Scraping.pdf) / [Code](/src/webscrape_examples.ipynb)

## Installation Guide

1. Create environment:
```bash
conda create -n webscrape python=3.12
```

2. Activate environment:
```bash
conda activate webscrape
```

3. Install uv:
```bash
pip install uv
```

4. Install dependencies:
```bash
uv pip install -r requirements.txt
```

5. Install Playwright:
```bash
playwright install
```

## Environment Setup

Create a `.env` file with:
```plaintext
LITELLM_API_KEY=
LITELLM_URL=
```

---
