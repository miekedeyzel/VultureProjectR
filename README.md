# The Effects of Climate Change on the Breeding Ecology of African White-backed Vultures: Analyses  
### MSc in Conservation Biology – University of Cape Town  
**Author:** Mieke Deyzel  

---

## Overview

This repository accompanies my MSc research examining how climate change influences the breeding ecology of African White-backed Vultures (*Gyps africanus*) at Dronfield Nature Reserve (1993–2024).

The project integrates long-term breeding monitoring data with climatic variables to assess how weather affects:

- Number of active nests  
- Breeding success  
- Breeding timing  

This repository provides rendered outputs and reproducible analytical code to support transparency, academic examination, and methodological clarity.

---

## How to Get Started

### View the Results Directly

You can access the rendered documents directly:

- **Analysis.pdf** – Full statistical appendix (code and outputs)  
- **Analysis.html** – Interactive version  
- **Writing.pdf** – Thesis manuscript  

### Reproduce the Analysis

Requirements:

- R (≥ 4.0)  
- Quarto  

Clone the repository:

```bash
git clone https://github.com/miekedeyzel/VultureProjectR.git
```

Install required R packages:

```r
install.packages(c("tidyverse", "lme4", "AICcmodavg", "ggplot2"))
```

Render the analysis:

```bash
quarto render Analysis.qmd --to pdf
```

---

## Contribution Guidelines

This repository is shared to support academic transparency and reproducibility.

Contributions, suggestions, or methodological discussions are welcome via:

- GitHub Issues  
- Direct contact with the author  

License:  
This repository is provided for academic and research purposes.  
Data and materials may not be redistributed or reused without permission.

Contact:  
Mieke Deyzel  
University of Cape Town  
miekedeyzel1@icloud.com  

---

## File Structure

```
VultureProjectR/
│
├── README.md
│
├── outputs/
│   ├── Analysis.pdf
│   ├── Analysis.html
│   └── Writing.pdf
│
├── code/
│   └── Analysis.qmd
│
├── data/
│   └── 93_24 cleaned.csv
│
├── refs/
│   ├── References.bib
│   └── elsevier-harvard2.csl
```
