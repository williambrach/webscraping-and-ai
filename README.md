# Is the Future of Web Scraping Agentic?
A comprehensive exploration of modern web scraping techniques that combine traditional approaches with AI-powered agents. This repository demonstrates the evolution from static scraping to intelligent, autonomous web data extraction using LLMs and agent frameworks.
# Overview
Traditional web scraping follows a linear pipeline: Discover → Crawl → Scrape → Extract. Agentic scraping introduces intelligent decision-making, adaptive strategies, and autonomous navigation through AI agents that can reason about web content and interactions.
## Content

- CODECON 2025 #BRATISLAVA  [Slides](/slides/CODECON%202025%20Web%20Scraping%20Agents.pdf) / [Code](/src/) / [Video](https://www.youtube.com/watch?v=l3dj5huaJwM)
- CODECON 2024 #ZILINA  [Slides](https://github.com/williambrach/webscraping-and-ai/blob/codecon-2024/slides/CODECON%202024%20AI%20Scraping.pdf) / [Code](https://github.com/williambrach/webscraping-and-ai/blob/codecon-2024/src/webscrape_examples.ipynb) / [Video](https://www.youtube.com/watch?v=fhTsBuzMmVI)

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

