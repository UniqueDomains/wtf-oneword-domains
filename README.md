# Available .WTF One-Word Domains (5,622,106)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-7%2C790%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-5%2C622%2C106%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .wtf one-word domains from Unique Domains.

> **Important:** this repository is a **public 7,790-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **5,622,106 domains** on the canonical page below.

**Public extract:** 7,790 rows · **Live catalog:** 5,622,106 domains

**Last updated:** 2026-04-10  
**Canonical page:** `https://unique.domains/domains/tld/wtf`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/wtf?utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./wtf.csv">CSV</a> / <a href="./wtf.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .WTF search](https://unique.domains/domains/tld/wtf?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .WTF search](https://unique.domains/domains/tld/wtf?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .WTF one-word domain catalog.

### Files

- `wtf.csv` — public CSV extract (7,790 rows)
- `wtf.json` — public JSON extract (7,790 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/wtf-oneword-domains/main/wtf.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| nimble.wtf    | available | $5.99     | $46.99        | 94             | 33     | 6      | name.com          |
| eleven.wtf    | resell    | $5.99     | $46.99        | 88             | 34     | 6      | Spaceship, Inc.   |
| property.wtf  | premium   | $42.90    | $42.90        | 90             | 41     | 8      | namecheap         |
| adaptive.wtf  | available | $5.99     | $46.99        | 76             | 32     | 8      | name.com          |
| concrete.wtf  | resell    | $5.99     | $46.99        | 102            | 31     | 8      | Spaceship, Inc.   |
| total.wtf     | premium   | $250      | $250          | 108            | 38     | 5      | name.com          |
| second.wtf    | available | $5.99     | $46.99        | 120            | 28     | 6      | name.com          |
| leap.wtf      | resell    | —         | —             | 76             | 99     | 4      | Dynadot Inc       |
| personal.wtf  | premium   | $85.80    | $85.80        | 91             | 35     | 8      | namecheap         |
| curative.wtf  | available | $5.99     | $46.99        | 92             | 27     | 8      | name.com          |
| select.wtf    | resell    | —         | —             | 74             | 99     | 6      | Dynadot Inc       |
| tour.wtf      | premium   | $128.70   | $128.70       | 72             | 35     | 4      | namecheap         |
| outside.wtf   | available | $5.99     | $46.99        | 60             | 26     | 7      | name.com          |
| beast.wtf     | resell    | —         | —             | 64             | 98     | 5      | Dynadot Inc       |
| dental.wtf    | premium   | $41.25    | $41.25        | 90             | 34     | 6      | name.com          |
| different.wtf | available | $5.99     | $46.99        | 100            | 25     | 9      | name.com          |
| checkout.wtf  | resell    | —         | —             | 68             | 79     | 9      | Sav.com, LLC - 15 |
| expert.wtf    | premium   | $123.75   | $123.75       | 104            | 32     | 6      | name.com          |
| release.wtf   | available | $49.48    | —             | 98             | 25     | 7      | namecheap         |
| get.wtf       | resell    | —         | —             | 88             | 69     | 3      | Spaceship, Inc.   |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 7,790-row public sample | 5,622,106 live domains                           |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/wtf?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/wtf?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .WTF One-Word Domains*. Version 2026-04-10. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .WTF page](https://unique.domains/domains/tld/wtf?utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
