# Available .NEXUS One-Word Domains (18,679)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-18%2C679%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .nexus one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **18,679 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 18,679 domains · **Median ask:** $75.49 · **High-demand under $2,500:** 28

**Last updated:** 2026-08-22
**Canonical page:** `https://unique.domains/domains/tld/nexus`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/nexus?utm_source=github&utm_medium=referral&utm_campaign=repo_nexus_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./nexus.csv">CSV</a> / <a href="./nexus.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_nexus_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_nexus_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .NEXUS search](https://unique.domains/domains/tld/nexus?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_nexus_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .NEXUS search](https://unique.domains/domains/tld/nexus?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_nexus_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_nexus_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .NEXUS one-word domain catalog.

### Files

- `nexus.csv`, public CSV extract (1,000 rows)
- `nexus.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/nexus-oneword-domains/main/nexus.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain     | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ---------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| achy.nexus | available | $12.98    | $15.98        | low            | low    | 4      | namecheap |
| ada.nexus  | premium   | $311.25   | —             | medium         | medium | 3      | name.com  |
| ague.nexus | available | $12.98    | $15.98        | low            | low    | 4      | namecheap |
| ape.nexus  | premium   | $161.25   | $161.25       | medium         | low    | 3      | name.com  |
| awry.nexus | available | $12.98    | $15.98        | low            | low    | 4      | namecheap |
| awe.nexus  | premium   | $73.75    | —             | high           | low    | 3      | name.com  |
| clxx.nexus | available | $12.98    | $15.98        | low            | low    | 4      | namecheap |
| bag.nexus  | premium   | $623.75   | —             | high           | low    | 3      | name.com  |
| flee.nexus | available | $15.98    | —             | medium         | low    | 4      | namecheap |
| bee.nexus  | premium   | $623.75   | —             | high           | medium | 3      | name.com  |
| ilxx.nexus | available | $12.98    | $15.98        | low            | low    | 4      | namecheap |
| ben.nexus  | premium   | $623.75   | —             | high           | medium | 3      | name.com  |
| Jody.nexus | available | $15.98    | —             | high           | low    | 4      | namecheap |
| clx.nexus  | premium   | $73.75    | $73.75        | low            | low    | 3      | name.com  |
| lxxx.nexus | available | $12.98    | $15.98        | low            | low    | 4      | namecheap |
| dip.nexus  | premium   | $161.25   | $161.25       | high           | low    | 3      | name.com  |
| numb.nexus | available | $15.98    | —             | high           | low    | 4      | namecheap |
| due.nexus  | premium   | $311.25   | —             | high           | low    | 3      | name.com  |
| pail.nexus | available | $15.98    | —             | high           | low    | 4      | namecheap |
| Eid.nexus  | premium   | $311.25   | —             | high           | low    | 3      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 18,679 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 28 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/nexus?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_nexus_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/nexus?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_nexus_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_nexus_oneword_domains&utm_content=related_pricing)

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

This list contains 12,721 one-word domain names on the .nexus extension, with a median asking price near $115.55. Names like FinalFour.nexus, shoparound.nexus, and cuddleup.nexus show the style: short, expressive, single-word phrases that read naturally as brands. Because .nexus is a newer extension, pricing tends to stay accessible while still offering room for distinctive, ownable names across many themes — from lifestyle terms to descriptive action phrases.

- 12,721 one-word .nexus domains available for comparison
- Median asking price near $116 per domain
- Examples: homes.nexus, pictures.nexus, cuddleup.nexus
- Short, brandable, single-word style throughout

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .NEXUS One-Word Domains*. Version 2026-08-22. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .NEXUS page](https://unique.domains/domains/tld/nexus?utm_source=github&utm_medium=referral&utm_campaign=repo_nexus_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_nexus_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_nexus_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_nexus_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
