# Web Scraping and AI

A collection of modern web scraping techniques and implementations that combine traditional scraping with AI capabilities. The repository showcases different approaches from traditional BeautifulSoup to LLM-powered solutions, with concrete examples, performance metrics, and cost analysis.

## Content

- CODECON 2024 #ZILINA  [Slides](https://github.com/williambrach/webscraping-and-ai/blob/codecon-2024/slides/CODECON%202024%20AI%20Scraping.pdf) / [Code](https://github.com/williambrach/webscraping-and-ai/blob/codecon-2024/src/webscrape_examples.ipynb) / [Video](https://www.youtube.com/watch?v=fhTsBuzMmVI)
- CODECON 2025 #BRATISLAVA  [Slides](/slides/) / [Code](/src/) / [Video]()

## Installation Guide

1. Create environment:
```bash
uv venv --python 3.12
```

2. Activate environment:
```bash
source .venv/bin/activate
```

3. Install dependencies:
```bash
uv sync
```

4. Install Playwright:
```bash
uv run playwright install chromium
```

## Environment Setup

Create a `.env` file with:
```plaintext
LITELLM_API_KEY=
LITELLM_URL=
FIRECRAWL_API_KEY=
```

