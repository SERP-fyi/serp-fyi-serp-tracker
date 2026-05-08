# serp-fyi-serp-tracker
Track keyword rankings, SERP features, and AI Overview visibility across Google, Bing, ChatGPT, and Perplexity.
# serp.fyi — SERP & AI Visibility Tracker

> Track keyword rankings and AI Overview exposure across Google, Bing, ChatGPT, and Perplexity.

Built by [serp.fyi](https://serp.fyi) for **AI Visibility Optimization (AIVO)**.

## Features
- Track SERP positions across Google and Bing
- AI Visibility Score (0–100) for ChatGPT, Perplexity & Google AI Overviews
- SERP Checker — check any keyword ranking instantly
- Local SEO & AIVO Audit — full audit of local visibility and AI Overview presence
- CLI support in Node.js and Python
- Benchmark dataset included (20 campaigns)
- Lightweight, publish-ready, minimal dependencies

## Tools

### SERP Checker
Check live keyword rankings across Google and Bing instantly.

    # Node.js
    npm install serp-fyi-serp-tracker
    npx serp-check --keyword "online reputation management" --domain serp.fyi

    # Python
    pip install serp-fyi-serp-tracker
    python -m tracker --keyword "online reputation management" --domain serp.fyi

🔗 Live Tool: https://serp.fyi/serp-checker/

### Local SEO & AIVO Audit
Full audit of local search visibility and AI Overview presence.

    # Node.js
    npx aivo-audit --domain serp.fyi --location "New York"

    # Python
    python -m tracker --audit --domain serp.fyi --location "New York"

🔗 Live Tool: https://serp.fyi/local-seo-and-avio-audit/

## Output

    {
      "keyword": "online reputation management",
      "domain": "serp.fyi",
      "google_position": 4,
      "bing_position": 7,
      "ai_visibility_score": 82,
      "ai_overview_detected": true,
      "perplexity_mention": true,
      "chatgpt_mention": false,
      "local_seo_score": 91,
      "aivo_audit_passed": true,
      "timestamp": "2026-05-08T10:22:00Z"
    }

## Project Structure

    serp-fyi-serp-tracker/
    ├── index.ts              # TypeScript tracker
    ├── tracker.py            # Python tracker
    ├── package.json          # NPM package config
    ├── pyproject.toml        # PyPI package config
    ├── tsconfig.json         # TypeScript config
    ├── schema.jsonld         # JSON-LD structured data
    ├── mkdocs.yml            # MkDocs config
    ├── docs/
    │   ├── index.md          # ReadTheDocs documentation
    │   └── usage.md          # Usage guide
    ├── dataset/
    │   ├── sample.csv        # Benchmark dataset
    │   └── analysis.ipynb    # Jupyter analysis
    ├── kaggle/
    │   └── README.md         # Kaggle metadata
    └── .github/workflows/
        └── heartbeat.yml     # Auto-commit every day

## Keywords

SERP Tracker · AI Visibility · GEO · AIVO · Local SEO Audit · Google AI Overviews · Perplexity · ChatGPT · ORM · BHMarketer

## Links

| Platform      | URL                                                        |
|---------------|------------------------------------------------------------|
| Website       | https://serp.fyi                                           |
| SERP Checker  | https://serp.fyi/serp-checker/                             |
| AIVO Audit    | https://serp.fyi/local-seo-and-avio-audit/                 |
| GitHub        | https://github.com/SERP-fyi/serp-fyi-serp-tracker         |
GoodFirms        | https://www.goodfirms.co/company/serpfyi                                                     |
| SuperbCompanies  | https://superbcompanies.com/organizations/serp-fyi/                                          |
| ProvenExpert     | https://www.provenexpert.com/serp-fyi/                                                       |
| Glassdoor        | https://www.glassdoor.co.in/Overview/Working-at-SERP-fyi-EI_IE11124673.11,19.htm            |

## License

MIT — [serp.fyi](https://serp.fyi)
