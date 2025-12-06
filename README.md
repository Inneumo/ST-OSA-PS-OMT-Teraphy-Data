# Orofacial Myofunctional Therapy Survivor Dataset

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![DOI: 10.1016/j.rmed.2025.108460](https://zenodo.org/badge/DOI/10.1016/j.rmed.2025.108460.svg)](https://doi.org/10.1016/j.rmed.2025.108460)
![GitHub last commit](https://img.shields.io/github/last-commit/Inneumo/ST-OSA-PS-OMT-Teraphy-Data)
[![FAIR Compliance](https://img.shields.io/badge/FAIR-Data-blue)](https://www.go-fair.org/fair-principles/)
![GitHub repo size](https://img.shields.io/github/repo-size/Inneumo/ST-OSA-PS-OMT-Teraphy-Data)
[![Open Science](https://img.shields.io/badge/open%20science-yes-brightgreen)](https://www.fosteropenscience.eu/)

**Description**:  

This dataset supports the study _"Artificial Intelligence-Enhanced Telemedicine for Orofacial Myofunctional Therapy in Sleep Apnea: Adult Patient Outcomes"_. It includes anonymized clinical and treatment response data from 87 adult patients who underwent AI-assisted Orofacial Myofunctional Therapy (OMT) using the Smart Therapy Manager® system, aimed at treating Obstructive Sleep Apnea (OSA) and Primary Snoring (PS).

---

## Table of Contents

- [Orofacial Myofunctional Therapy Survivor Dataset](#orofacial-myofunctional-therapy-survivor-dataset)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Dataset Structure](#dataset-structure)
  - [Usage](#usage)
  - [✅ FAIR Compliance](#-fair-compliance)
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
- [`docs/`](docs/): Methodology, ethical approval, and contextual information.
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
author = {{Rivera Capacho}, Eliana Elizabeth and Bossa, Claudia Patricia Diaz and Campos, Mar{\'{i}}a Del Carmen and Rincon-Yanez, Diego and Rangel-Navia, Heriberto and Bianchini, Esther Mandelbaum Gon{\c{c}}alves},
doi = {10.1016/j.rmed.2025.108460},
issn = {15323064},
journal = {Respiratory medicine},
month = {nov},
pmid = {41176093},
title = {{Telemedicine-supported structured Orofacial Myofunctional Therapy model for Obstructive Sleep Apnea: Patients' report outcomes measurements}},
volume = {249},
year = {2025}
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

