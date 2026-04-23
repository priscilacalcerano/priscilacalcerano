# Hi, I'm Priscila 👋

GTM Engineer working at the intersection of B2B sales operations, data engineering, and automation. Based in Barcelona 🇪🇸

I build the systems that turn raw prospect data into actionable outbound pipelines: territory segmentation, contact deduplication, channel routing logic, and weekly campaign delivery. I also apply machine learning to real sales problems, including predictive lead scoring trained on live outbound data.

---

## What I do

**Pipeline & data engineering**
Design and automate B2B prospecting pipelines: cleaning and normalizing CRM exports, deduplicating by domain and LinkedIn URL, applying business logic (contact caps, territory assignment, language callability), and generating segmented, channel-ready output files.

**GTM systems & campaign operations**
End-to-end campaign management across 15+ client accounts simultaneously, configuring outreach identities, warmup, sequences, and enrichment workflows in Enginy and Clay. Multi-BDR territory splits, exclusion logic, and weekly prioritization at scale. Clients include enterprise software companies, Microsoft Gold Partners, and global technology vendors.

**Applied ML for sales**
Built a LightGBM lead scoring model on real outbound prospecting data (~6,000 contacts, 14% positive rate). Features include engineered signals from LinkedIn enrichment, K-Means cluster membership, and job title embeddings compressed with UMAP. Evaluated with PR-AUC and Precision@100 due to class imbalance. Achieved 2.6x lift in top 10%, meaning 25 extra sales conversations per week at zero additional cost.

---

## Tech stack

```
Languages     Python
GTM tools     Enginy · Clay · Apollo · Prospeo · LinkedIn Sales Navigator
ML            LightGBM · XGBoost · scikit-learn · K-Means · UMAP · SHAP · Optuna
Automation    Python scripting · Claude Code · API basics
```

---

## Projects

### [tfm-lead-scoring-b2b](https://github.com/priscilacalcerano/tfm-lead-scoring-b2b)
LightGBM classifier trained on real outbound prospecting data from a Microsoft Gold Partner's sales team. Features combine engineered signals from LinkedIn enrichment data, K-Means segmentation, and dimensionality-reduced job title embeddings. SHAP analysis revealed that mid-level decision makers (VPs, Directors) outperform C-level contacts by 2x in response rate, a finding that directly challenged the client's targeting assumptions.

`python` `lightgbm` `umap` `shap` `optuna` `kmeans` `sales-ml`

### [outbound-contact-segmentation](https://github.com/priscilacalcerano/outbound-contact-segmentation)
Python pipeline that takes raw CRM exports and produces segmented, channel-ready contact lists for a B2B outbound team of 4 BDRs across LATAM, EMEA, Spain, and Italy. Handles territory assignment, buyer/influencer/referrer caps, language-based call routing, 3-month backup reserves, and formatted Excel summaries for weekly briefings.

`python` `pandas` `b2b-sales` `gtm` `data-pipeline`

### [mi_scraper](https://github.com/priscilacalcerano/mi_scraper)
Web scraping pipeline for public procurement data that extracts and structures bid listings for commercial targeting.

`python` `web-scraping` `b2b-sales`

---

## Background

2 years as BDR, then 1 year as GTM Engineer at a B2B sales consultancy managing outbound infrastructure for 15+ simultaneous client accounts across cybersecurity, enterprise software, staff augmentation, HR and e-commerce. MSc in Data Science & AI, Nuclio Digital School.

The combination is unusual: most GTM engineers don't have ML training, and most data scientists have never configured a BDR identity or written a cold outreach sequence. I work in both.

---

## Currently

📍 Barcelona, Spain

🎓 MSc Data Science & AI, Nuclio Digital School

💼 GTM Engineer, B2B sales consultancy

🔗 [LinkedIn](https://www.linkedin.com/in/priscilacalcerano)
