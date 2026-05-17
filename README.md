# Available .IMMO One-Word Domains (12,218)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C218%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .immo one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,218 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,218 domains · **Median ask:** $19.06 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-17  
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

- `immo.csv` — public CSV extract (1,000 rows)
- `immo.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/immo-oneword-domains/main/immo.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| Trex.immo     | available | $43.98    | —             | 80             | 24     | 5      | namecheap |
| finals.immo   | available | $14.99    | —             | 80             | 7      | 6      | name.com  |
| ladies.immo   | available | $14.99    | —             | 80             | 17     | 6      | name.com  |
| barup.immo    | available | $14.99    | —             | 82             | 2      | 6      | name.com  |
| geton.immo    | available | $14.99    | —             | 82             | 10     | 6      | name.com  |
| getup.immo    | available | $14.99    | —             | 82             | 15     | 6      | name.com  |
| matcha.immo   | available | $14.99    | —             | 86             | 39     | 6      | name.com  |
| dogsit.immo   | available | $14.99    | —             | 96             | 2      | 6      | name.com  |
| gearup.immo   | available | $14.99    | —             | 80             | 16     | 7      | name.com  |
| toneup.immo   | available | $14.99    | —             | 80             | 5      | 7      | name.com  |
| pierogi.immo  | available | $14.99    | —             | 82             | 7      | 7      | name.com  |
| dogsick.immo  | available | $14.99    | —             | 90             | 1      | 7      | name.com  |
| Books.immo    | available | $43.98    | —             | 52             | 49     | 5      | namecheap |
| agents.immo   | premium   | $250      | —             | 56             | 50     | 6      | name.com  |
| events.immo   | premium   | $123.75   | —             | 68             | 37     | 6      | name.com  |
| lets.immo     | available | $14.99    | —             | 77             | 39     | 4      | name.com  |
| SanDiego.immo | premium   | $242      | $242          | 74             | 29     | 9      | namesilo  |
| aliens.immo   | available | $14.99    | —             | 56             | 35     | 6      | name.com  |
| photos.immo   | premium   | $123.75   | —             | 54             | 28     | 6      | name.com  |
| spectra.immo  | available | $14.99    | —             | 62             | 34     | 7      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,218 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/immo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/immo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is entirely made up of .immo domains, which makes extension fit the first filter. The strongest names read naturally with real-estate intent, stay easy to say, and look credible when paired with property, agency, rental, or regional positioning. Examples such as Acup.immo, Trex.immo, girls.immo, WiFi.immo, and jewels.immo show how mixed the word quality can be: some are flexible and memorable, while others feel disconnected from the extension. With a median ask of 19.06, these domains can be inexpensive to secure, but low price alone does not make a name strong. Focus on clarity, sector relevance, and whether the word still makes sense to a buyer or end user in .immo.

- Prioritize words that make obvious sense with .immo
- Low ask helps, but weak extension fit still limits upside
- Favor short, clean words with clear spoken recall
- Check trademark signals before valuing brandability

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .IMMO One-Word Domains*. Version 2026-05-17. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .IMMO page](https://unique.domains/domains/tld/immo?utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_immo_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
