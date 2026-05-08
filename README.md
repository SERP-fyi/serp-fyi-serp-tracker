# serp.fyi — AI Visibility & SERP Intelligence Tracker

> Track keyword rankings, SERP features, and AI Overview visibility across Google, Bing, ChatGPT, and Perplexity.

Built by [serp.fyi](https://serp.fyi) for **AI Visibility Optimization (AIVO)** and next-generation search intelligence workflows.

## Features

- Track SERP rankings across Google and Bing
- Monitor AI visibility across ChatGPT, Perplexity, and Google AI Overviews
- AI Visibility Score (0–100) for brands, keywords, and domains
- SERP Checker — instantly analyze live keyword rankings and SERP features
- Local SEO & AIVO Audit — full audit of local rankings, map visibility, reviews, and AI Overview exposure
- Detect SERP features including:
  - AI Overviews
  - Local Pack
  - Featured Snippets
  - Knowledge Graphs
  - Video & Image Packs
- Search intent and authority analysis
- Competitor SERP intelligence and ranking comparison
- CLI support for Node.js and Python
- Benchmark dataset included (20 campaigns)
- Lightweight, API-ready, publish-ready architecture with minimal dependencies

## Tools

### SERP Checker
Analyze live keyword rankings and SERP structure across Google and Bing.

    # Node.js
    npm install serp-fyi-serp-tracker
    npx serp-check --keyword "online reputation management" --domain serp.fyi

    # Python
    pip install serp-fyi-serp-tracker
    python -m tracker --keyword "online reputation management" --domain serp.fyi

🔗 Live Tool: https://serp.fyi/serp-checker/

### Local SEO & AIVO Audit
Audit local search visibility, map rankings, review signals, and AI Overview presence.

    # Node.js
    npx aivo-audit --domain serp.fyi --location "New York"

    # Python
    python -m tracker --audit --domain serp.fyi --location "New York"

🔗 Live Tool: https://serp.fyi/local-seo-and-avio-audit/

## Example Output

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
        └── heartbeat.yml     # Daily automation workflow

## Use Cases

- Track AI Overview exposure for branded keywords
- Monitor local SEO rankings and Google Maps visibility
- Analyze SERP competition and authority signals
- Audit AI search visibility for brands and businesses
- Compare competitor visibility across search engines and AI systems
- Build AI Visibility Optimization workflows

## Supported Platforms

| Platform            | Support |
|---------------------|---------|
| Google Search       | ✅      |
| Bing                | ✅      |
| Google AI Overviews | ✅      |
| ChatGPT             | ✅      |
| Perplexity          | ✅      |

## Keywords

SERP Tracker · AI Visibility · AIVO · GEO · AI SEO · SERP Checker · AI Overview Tracker · Local SEO Audit · ChatGPT Visibility · Perplexity Visibility · Google AI Overviews · SERP Feature Tracker · Search Intent Analysis · Competitor SERP Analysis · Local Ranking Checker · Google Business Profile Audit · Local SERP Analyzer · ORM · AI Search Optimization

## Links

| Platform          | URL                                                                                   |
|-------------------|---------------------------------------------------------------------------------------|
| Website           | https://serp.fyi                                                                      |
| SERP Checker      | https://serp.fyi/serp-checker/                                                        |
| Local SEO & AIVO  | https://serp.fyi/local-seo-and-avio-audit/                                            |
| GitHub            | https://github.com/SERP-fyi/serp-fyi-serp-tracker                                    |
| GoodFirms         | https://www.goodfirms.co/company/serpfyi                                              |
| SuperbCompanies   | https://superbcompanies.com/organizations/serp-fyi/                                   |
| ProvenExpert      | https://www.provenexpert.com/serp-fyi/                                                |
| Glassdoor         | https://www.glassdoor.co.in/Overview/Working-at-SERP-fyi-EI_IE11124673.11,19.htm     |
| Kaggle            | https://www.kaggle.com/serpfyi                                                        |
| Hugging Face      | https://huggingface.co/serp-fyi                                                       |


## License

MIT — [serp.fyi](https://serp.fyi)
