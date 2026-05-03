# Available .TODAY One-Word Domains (9,985)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-9%2C985%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .today one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **9,985 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 9,985 domains

**Last updated:** 2026-05-03  
**Canonical page:** `https://unique.domains/domains/tld/today`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/today?utm_source=github&utm_medium=referral&utm_campaign=repo_today_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./today.csv">CSV</a> / <a href="./today.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_today_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_today_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .TODAY search](https://unique.domains/domains/tld/today?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_today_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .TODAY search](https://unique.domains/domains/tld/today?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_today_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_today_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .TODAY one-word domain catalog.

### Files

- `today.csv` — public CSV extract (1,000 rows)
- `today.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/today-oneword-domains/main/today.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| gods.today         | available | $2.99     | —             | 72             | 27     | 4      | name.com        |
| online.today       | resell    | —         | —             | 70             | 62     | 7      | DNSPod, Inc.    |
| has.today          | premium   | $123.75   | —             | 60             | 26     | 3      | name.com        |
| rekt.today         | available | $2.99     | —             | 40             | 24     | 4      | name.com        |
| fit.today          | resell    | —         | —             | 88             | 41     | 3      | Spaceship, Inc. |
| accountants.today  | premium   | $118.80   | $118.80       | 50             | 16     | 11     | namesilo        |
| superhero.today    | available | $2.99     | —             | 84             | 23     | 9      | name.com        |
| dave.today         | resell    | —         | —             | 76             | 38     | 4      | Dynadot Inc     |
| Phillip.today      | premium   | $138.60   | $138.60       | 70             | 14     | 7      | namecheap       |
| webshop.today      | available | $2.99     | —             | 76             | 22     | 8      | name.com        |
| tokens.today       | resell    | —         | —             | 51             | 36     | 6      | Dynadot Inc     |
| motorsports.today  | premium   | $123.75   | —             | 74             | 13     | 11     | name.com        |
| stadia.today       | available | $2.99     | —             | 66             | 22     | 6      | name.com        |
| Cats.today         | resell    | —         | —             | 59             | 33     | 4      | Sav.com, LLC    |
| parties.today      | premium   | $250      | —             | 58             | 13     | 7      | name.com        |
| Alexis.today       | available | $2.99     | —             | 72             | 21     | 6      | name.com        |
| trends.today       | resell    | —         | —             | 60             | 32     | 6      | Name.com, Inc.  |
| universities.today | premium   | $250      | —             | 54             | 9      | 12     | name.com        |
| stores.today       | available | $2.99     | —             | 62             | 20     | 6      | name.com        |
| velvet.today       | resell    | —         | —             | 80             | 31     | 6      | Spaceship, Inc. |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 1,000-row public sample | 9,985 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/today?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_today_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/today?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_today_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_today_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .TODAY One-Word Domains*. Version 2026-05-03. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .TODAY page](https://unique.domains/domains/tld/today?utm_source=github&utm_medium=referral&utm_campaign=repo_today_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_today_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_today_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_today_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
