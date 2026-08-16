# Available .IMMO One-Word Domains (15,852)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C852%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .immo one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,852 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,852 domains · **Median ask:** $18.35 · **High-demand under $2,500:** 2

**Last updated:** 2026-08-16
**Canonical page:** `https://unique.domains/domains/tld/immo`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/immo?utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./immo.csv">CSV</a> / <a href="./immo.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .IMMO search](https://unique.domains/domains/tld/immo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .IMMO search](https://unique.domains/domains/tld/immo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .IMMO one-word domain catalog.

### Files

- `immo.csv`, public CSV extract (1,000 rows)
- `immo.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/immo-oneword-domains/main/immo.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| age.immo     | available | $14.99    | —             | high           | low    | 3      | name.com          |
| buy.immo     | resell    | —         | —             | medium         | medium | 3      | Dynadot Inc       |
| kid.immo     | premium   | $242      | $242          | high           | low    | 3      | namesilo          |
| ale.immo     | available | $14.99    | —             | medium         | low    | 3      | name.com          |
| game.immo    | resell    | —         | —             | high           | medium | 4      | Sav.com, LLC - 42 |
| mon.immo     | premium   | $250      | —             | high           | low    | 3      | name.com          |
| bee.immo     | available | $14.99    | —             | high           | medium | 3      | name.com          |
| viewer.immo  | resell    | —         | —             | medium         | low    | 6      | IONOS SE          |
| NYC.immo     | premium   | $118.80   | $118.80       | high           | medium | 3      | namesilo          |
| boo.immo     | available | $14.99    | —             | high           | low    | 3      | name.com          |
| builder.immo | resell    | —         | —             | high           | low    | 7      | Sav.com, LLC      |
| pad.immo     | premium   | $242      | $242          | medium         | low    | 3      | namesilo          |
| bro.immo     | available | $14.99    | —             | medium         | low    | 3      | name.com          |
| harmony.immo | resell    | —         | —             | high           | medium | 7      | Sav.com, LLC - 29 |
| fund.immo    | premium   | $78.54    | $78.54        | high           | low    | 4      | namesilo          |
| con.immo     | available | $14.99    | —             | medium         | low    | 3      | name.com          |
| spot.immo    | premium   | $78.54    | $78.54        | high           | medium | 4      | namesilo          |
| cry.immo     | available | $14.99    | —             | high           | low    | 3      | name.com          |
| star.immo    | premium   | $123.75   | $123.75       | high           | medium | 4      | name.com          |
| don.immo     | available | $14.99    | —             | high           | low    | 3      | name.com          |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,852 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 2 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/immo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/immo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list gathers one-word and short-phrase .immo domain names, a TLD often used for real estate, property, and home-services branding. The median asking price sits near $20, making most entries accessible for quick acquisition. Names range from literal phrases like getmarried.immo and dogsit.immo to abstract, brandable picks like superhero.immo and midmorning.immo — giving investors a low-cost entry point and founders a fast shortlist of ownable, memorable names.

- 12,218 available one-word .immo domains, updated daily
- Median asking price near $20 across this selection
- Real estate, lifestyle, and service-brand ready names
- Includes phrases like getmarried.immo and superhero.immo

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .IMMO One-Word Domains*. Version 2026-08-16. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .IMMO page](https://unique.domains/domains/tld/immo?utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
