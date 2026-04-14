# Available .DIRECTORY One-Word Domains (8,618)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-8%2C620%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-8%2C618%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .directory one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 8,620 rows · **Live catalog:** 8,618 domains

**Last updated:** 2026-04-14  
**Canonical page:** `https://unique.domains/domains/tld/directory`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/directory?utm_source=github&utm_medium=referral&utm_campaign=repo_directory_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./directory.csv">CSV</a> / <a href="./directory.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_directory_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_directory_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .DIRECTORY search](https://unique.domains/domains/tld/directory?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_directory_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .DIRECTORY search](https://unique.domains/domains/tld/directory?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_directory_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_directory_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .DIRECTORY one-word domain catalog.

### Files

- `directory.csv` — public CSV extract (8,620 rows)
- `directory.json` — public JSON extract (8,620 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/directory-oneword-domains/main/directory.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                   |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------- |
| matt.directory      | available | $7.99     | —             | 72             | 71     | 4      | name.com                                    |
| kick.directory      | resell    | —         | —             | 98             | 80     | 4      | Porkbun LLC                                 |
| ace.directory       | premium   | $26       | $26           | 88             | 57     | 3      | namecheap                                   |
| shit.directory      | available | $7.99     | —             | 54             | 43     | 4      | name.com                                    |
| easy.directory      | resell    | —         | —             | 128            | 68     | 4      | Spaceship, Inc.                             |
| athletics.directory | premium   | $26       | $26           | 69             | 52     | 9      | namecheap                                   |
| awake.directory     | available | $7.99     | —             | 86             | 38     | 5      | name.com                                    |
| flow.directory      | resell    | —         | —             | 96             | 66     | 4      | Dynadot Inc                                 |
| travel.directory    | premium   | $1,000    | —             | 93             | 48     | 6      | name.com                                    |
| cozy.directory      | available | $7.99     | $33.99        | 110            | 37     | 4      | name.com                                    |
| home.directory      | resell    | —         | —             | 90             | 62     | 4      | Porkbun LLC                                 |
| big.directory       | premium   | $123.75   | $123.75       | 88             | 47     | 3      | name.com                                    |
| eclipse.directory   | available | $7.99     | —             | 72             | 37     | 7      | name.com                                    |
| open.directory      | resell    | —         | —             | 106            | 60     | 4      | GoDaddy Online Services Cayman Islands Ltd. |
| car.directory       | premium   | $1,040    | $1,040        | 94             | 46     | 3      | namecheap                                   |
| sharp.directory     | available | $7.99     | $33.99        | 84             | 36     | 5      | name.com                                    |
| pay.directory       | resell    | —         | —             | 84             | 60     | 3      | Sav.com, LLC                                |
| auto.directory      | premium   | $128.70   | $128.70       | 68             | 45     | 4      | namecheap                                   |
| yard.directory      | available | $7.99     | $33.99        | 80             | 35     | 4      | name.com                                    |
| cloud.directory     | resell    | —         | —             | 70             | 59     | 5      | Dynadot Inc                                 |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 8,620-row public sample | 8,618 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/directory?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_directory_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/directory?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_directory_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_directory_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .DIRECTORY One-Word Domains*. Version 2026-04-14. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DIRECTORY page](https://unique.domains/domains/tld/directory?utm_source=github&utm_medium=referral&utm_campaign=repo_directory_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_directory_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_directory_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_directory_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
