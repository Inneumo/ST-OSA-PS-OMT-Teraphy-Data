# Orofacial Myofunctional Therapy Survivor Dataset

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![GitHub repo size](https://img.shields.io/github/repo-size/Inneumo/ST-OSA-PS-OMT-Therapy-Data)
![GitHub last commit](https://img.shields.io/github/last-commit/Inneumo/ST-OSA-PS-OMT-Therapy-Data)
[![FAIR Compliance](https://img.shields.io/badge/FAIR-Data-blue)](https://www.go-fair.org/fair-principles/)

**Description**:  

This dataset supports the study _"Artificial Intelligence-Enhanced Telemedicine for Orofacial Myofunctional Therapy in Sleep Apnea: Adult Patient Outcomes"_. It includes anonymized clinical and treatment response data from 87 adult patients who underwent AI-assisted Orofacial Myofunctional Therapy (OMT) using the Smart Therapy Manager® system, aimed at treating Obstructive Sleep Apnea (OSA) and Primary Snoring (PS).

---

## Table of Contents

- [Overview](#overview)
- [Dataset Structure](#dataset-structure)
- [Usage](#usage)
- [FAIR Compliance](#fair-compliance)
- [Citation](#citation)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

---

## Overview

- **Study Type**: Retrospective Observational Cohort  
- **Period**: November 2021 – November 2022  
- **Location**: NEUMOMED Clinic, Medellín, Colombia  
- **Sample Size**: 87 patients  
- **Format**: CSV (FAIR-structured and anonymized)  
- **Target Use**: Clinical research, machine learning, sleep medicine, treatment outcome analysis.

---

## Dataset Structure

- [`data/`](data/): Original dataset as collected.
- [`metadata/`](metadata/): Metadata including variable descriptions and data dictionary.
- [`documentation/`](documentation/): Methodology, ethical approval, and contextual information.
- [`fair/`](fair/): FAIRness checklist and metadata standards.

---

## Usage

These instructions provide guidance on using the **Orofacial Myofunctional Therapy Survivor Dataset**. Please follow ethical standards when handling clinical data.

In Python (using Pandas):

```python
import pandas as pd
data = pd.read_csv('data/data_es.csv')
```

In R:

```r
data <- read.csv("data/data_es.csv")
```
---

## ✅ FAIR Compliance

This dataset follows the [FAIR Data Principles](https://www.go-fair.org/fair-principles/):

- **Findable**: DOI assigned and metadata indexed in open repositories  
- **Accessible**: Openly licensed under CC-BY 4.0 with no access restrictions  
- **Interoperable**: Provided in standard formats with machine-readable metadata  
- **Reusable**: Includes clear licensing, documentation, and citation guidelines

➡️ See [`fair/`](fair/) for a complete FAIR compliance breakdown.

---

## Citation

Please cite both the dataset and the corresponding paper:

```bibtex
@article{RiveraCapacho2025,
  title     = {Artificial Intelligence-Enhanced Telemedicine for Orofacial Myofunctional Therapy in Sleep Apnea: Adult Patient Outcomes},
  author    = {Rivera Capacho, Eliana Elizabeth and Diaz Bossa, Claudia Patricia and Campos, María del Carmen and Rincon-Yanez, Diego and Rangel-Navia, Heriberto and Bianchini, Esther Mandelbaum Gonçalves},
  journal   = {Submited to Respiratory Medicine},
  year      = {2025},
  note      = {Preprint submitted on January 19, 2025}
}
```

---

## Acknowledgments

- **NEUMOMED Sleep and Pulmonology Clinic**  
- **University of Pamplona**  
- All contributing authors and patients who consented to data usage

---

## Contact

If there are any troubles or you have any questions, please open an issue stating the encountered problem. Contributing is always welcome. The [Github repository Issues URL](https://github.com/Inneumo/ST-OSA-PS-OMT-Therapy-Data/issues).  And contributing is always welcome. The [Github repository URL](https://github.com/Inneumo/ST-OSA-PS-OMT-Therapy-Data).


Happy hacking!! 🖖🖖.

