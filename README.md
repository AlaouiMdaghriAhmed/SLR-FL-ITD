# 📊 DATA DESCRIPTION  
## Federated Learning for Insider Threat Detection (Systematic Literature Review)


The repository is structured to ensure **transparency, reproducibility, and methodological clarity**, following PRISMA-based review standards.

---


---

# 📂 Folder Descriptions

## 1️⃣ data/initial_search/

This folder contains all papers retrieved during the **initial database search phase**.

### Included sources:
- Scopus  
- Web of Science  
- IEEE Xplore  
- ACM Digital Library  
- SpringerLink  
- ScienceDirect  

### Contents:
- Raw search results  
- Duplicate entries (prior to removal)  
- Papers later excluded during screening  
- Full-text downloads when available  

This represents the complete search corpus before screening and filtering.

---

## 2️⃣ data/final_retained/

This folder contains the **final set of studies included in the SLR** after:

- Duplicate removal  
- Title and abstract screening  
- Full-text eligibility assessment  
- Inclusion and exclusion criteria application  

These papers form the validated dataset used for:

- Comparative analysis tables  
- Quantitative synthesis  
- Taxonomy construction  
- Methodological evaluation  
- Research gap identification  

This is the definitive corpus analyzed in the publication.

---

## 3️⃣ graph/

This directory contains the visual artifacts used in the article.

### 📊 graph/article_per_source/

Contains graphs illustrating:

- Number of articles retrieved per database  
- Distribution of initial search results across sources  

These figures support transparency in search strategy reporting.

![Articles per Source](graph/articles_per_source/articles_per_source.png)


---

### 📊 graph/retained_per_source/

Contains graphs illustrating:

- Number of retained studies per database  
- Impact of screening and eligibility filtering  

These figures provide insight into database contribution and filtering rigor.

---

# 🔎 Methodological Context

The dataset was constructed following:

- PRISMA guidelines  
- PICOC-based eligibility criteria  
- Explicit inclusion/exclusion rules  
- Multi-stage screening protocol  

The retained corpus was analyzed to:

- Evaluate federated learning architectures for ITD  
- Assess privacy-preserving mechanisms (e.g., Differential Privacy, SMPC, Secure Aggregation)  
- Compare defense strategies against poisoning and inference attacks  
- Identify open research challenges in FL-based insider threat detection  

---

# ♻️ Reproducibility & Extension

Researchers may:

- Reproduce the screening process  
- Validate inclusion/exclusion decisions  
- Re-generate visualizations  
- Extend the dataset with new publications  

If this dataset is reused, please cite the associated publication.

---

# ⚠️ Disclaimer

This repository contains academic publications collected for research purposes.

- Copyright remains with the original publishers.  
- Files are provided strictly for transparency and reproducibility.  
- Redistribution outside research context may require publisher permission.  

---

# 📌 Contact

For questions regarding the dataset or methodology, please open an issue in this repository.
