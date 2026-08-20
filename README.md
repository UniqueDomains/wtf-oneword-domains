# Available .WTF One-Word Domains (15,189)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C189%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .wtf one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,189 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,189 domains · **Median ask:** $6.94 · **High-demand under $2,500:** 0

**Last updated:** 2026-08-20
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

- `wtf.csv`, public CSV extract (1,000 rows)
- `wtf.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/wtf-oneword-domains/main/wtf.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain   | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| -------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| kgb.wtf  | available | $5.99     | —             | high           | low    | 3      | name.com          |
| aim.wtf  | resell    | —         | —             | high           | low    | 3      | NameCheap, Inc.   |
| age.wtf  | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo          |
| lay.wtf  | available | $5.99     | —             | medium         | low    | 3      | name.com          |
| con.wtf  | resell    | —         | —             | high           | low    | 3      | Sav.com, LLC - 33 |
| aid.wtf  | premium   | $118.80   | $118.80       | medium         | low    | 3      | namesilo          |
| lxx.wtf  | available | $2.98     | $49.48        | low            | low    | 3      | namecheap         |
| fly.wtf  | resell    | —         | —             | high           | low    | 3      | Dynadot Inc       |
| dew.wtf  | premium   | $78.54    | $78.54        | medium         | low    | 3      | namesilo          |
| UPC.wtf  | available | $5.99     | —             | high           | low    | 3      | name.com          |
| her.wtf  | resell    | —         | —             | medium         | low    | 3      | Sav.com, LLC - 44 |
| due.wtf  | premium   | $82.50    | —             | high           | low    | 3      | name.com          |
| xii.wtf  | available | $5.99     | $46.99        | medium         | low    | 3      | name.com          |
| jar.wtf  | resell    | —         | —             | high           | low    | 3      | Spaceship, Inc.   |
| lap.wtf  | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo          |
| acts.wtf | available | $5.99     | —             | medium         | low    | 4      | name.com          |
| now.wtf  | resell    | —         | —             | high           | medium | 3      | Porkbun LLC       |
| led.wtf  | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo          |
| agog.wtf | available | $2.98     | $49.48        | low            | low    | 4      | namecheap         |
| sup.wtf  | resell    | —         | —             | high           | low    | 3      | Sav.com, LLC - 11 |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,189 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/wtf?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/wtf?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=related_pricing)

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

These domains use the .WTF extension, known for its irreverent, memorable tone. Names in this set range from single words to short phrases like affirmation.wtf, makesense.wtf, and QandA.wtf, built for quick recall and playful branding. With a median ask near $10, this list suits founders testing an offbeat name and investors scanning a low-cost, high-volume TLD. Renewal cost and spelling clarity should still be checked per name before buying.

- 10,522 one-word .WTF domain names in this selection
- Median ask near $10 across the list
- Short, playful names built for brandable picks
- Check pricing and renewal before buying any name

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .WTF One-Word Domains*. Version 2026-08-20. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .WTF page](https://unique.domains/domains/tld/wtf?utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_wtf_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
