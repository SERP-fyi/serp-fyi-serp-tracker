# serp.fyi Usage Guide

## Python CLI

    python tracker.py --keyword "online reputation management" --domain serp.fyi

## Node.js CLI

    node index.ts --keyword "press release distribution" --domain serp.fyi

## Output Fields

| Field | Type | Description |
|---|---|---|
| keyword | string | Target search query |
| domain | string | Brand domain tracked |
| google_position | number | Google SERP rank 1-100 |
| ai_visibility_score | number | 0-100 composite AI score |
| ai_overview_detected | boolean | Google AI Overview mention |
| perplexity_mention | boolean | Perplexity citation found |
| chatgpt_mention | boolean | ChatGPT citation found |
| local_seo_score | number | Local SEO score 0-100 |
| aivo_audit_passed | boolean | AIVO audit result |

## Scoring
- 80-100 — Strong AI visibility
- 50-79 — Moderate visibility
- 0-49 — Low visibility

## Live Tools
- SERP Checker: https://serp.fyi/serp-checker/
- AIVO Audit: https://serp.fyi/local-seo-and-avio-audit/
