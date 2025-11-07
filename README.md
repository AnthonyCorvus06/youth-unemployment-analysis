# Youth Unemployment Analysis  
Difference-in-Differences Study of the 2008 Financial Crisis and the COVID-19 Pandemic

This repository contains the full analytical workflow, regression models, data processing scripts, and research outputs for a comparative study of youth unemployment trends in the United States across two major economic shocks: the 2008 Financial Crisis and the COVID-19 pandemic. All analysis is conducted in **R** with an emphasis on transparency and reproducibility.

##  Research Outputs

These are the final deliverables for the Institute of Computing Research internship:

- **`youth_unemployment_paper.pdf`** — Full research paper presenting theory, methods, results, and policy implications.  
- **`youth_unemployment_slides.pdf`** — Slide deck summarizing key findings and visualizations.

Both documents are derived entirely from the `analysis.R` script and its generated figures.

##  Overview of the Project

This study evaluates whether economic shocks disproportionately affect youth labor markets, and how policy responses during each crisis shaped recovery patterns.  
Key contributions include:

- **Difference-in-Differences (DiD)** regressions comparing youth (16–24) vs. adult (25+) unemployment.  
- **Visualizations** of labor force participation, unemployment gaps, and cohort disadvantages.  
- **Comparative policy analysis** between ARRA (2008) and CARES Act (2020).  
- **Discussion of long-term effects** such as scarring, hysteresis, and labor-market detachment.

## Reproducibility Instructions

All results, tables, and figures included in the paper and slides can be regenerated using the steps below.

### 1. Clone the repository### 1. Clone the repository
```bash
git clone https://github.com/AnthonyCorvus06/youth-unemployment-analysis.git
cd youth-unemployment-analysis
