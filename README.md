# Patent Intelligence Platform — Overview Deck

A short slide deck introducing the open-source patent intelligence platform to technology transfer offices and research institutions.

## View the deck

Open `index.html` in a browser, or view via GitHub Pages if enabled for this repo.

Uses [reveal.js](https://revealjs.com) served from CDN — no build step needed.

## What the platform does

1. **Acquires** patent and scholarly paper data from Lens.org (free API)
2. **Stores** structured metadata locally — jurisdiction, citations, family size, claims text
3. **Analyses** each patent using a local LLM with custom persona prompts (H/M/L risk tiering)
4. **Maps** results into technology family whitespace maps with geographic jurisdiction filters
5. **Links** academic papers to patents — tracking which research is being commercialised

Built with FastAPI · SQLite · HTMX · Docker · Ollama/local LLM.

## Case study

Applied to MXene EMI shielding adhesives: 14,000+ patents, 2,000+ papers, ~800 LLM-analyzed.
Primary EP blocker identified. Whitespace for EP provisional filings confirmed.
Total LLM compute cost: ~€0 marginal on local GPU.
