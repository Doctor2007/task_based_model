# AI Automation, Task Complexity, and Labour Market Outcomes

This repository contains the code and supporting materials for a study investigating how artificial intelligence expands automation across occupational tasks and how this affects wages, labour share, and economic output.

## Overview

Traditional automation models often represent technological progress as a one-dimensional expansion of machine capabilities. This project extends the task-based framework of Acemoglu & Restrepo by introducing a two-dimensional task space that separates:

* **Cognitive Complexity**
* **Physical Complexity**

Automation capability is modelled using a **Fisher-KPP reaction-diffusion process**, allowing machine knowledge to spread across related tasks while accounting for local learning effects.

The resulting automation surface is integrated into a **CES production framework** to examine the effects of automation on:

* Total output
* Wages
* Labour share

## Methods

### Quantitative

* Two-dimensional task complexity grid
* Fisher-KPP reaction-diffusion simulation
* CES production aggregation
* Sensitivity analysis across substitution elasticities (σ)

### Qualitative

* Close reading of O*NET task descriptions
* Structured questionnaire framework
* Complexity scoring for cognitive and physical task dimensions
* Case studies: Firefighter and Paediatric Surgeon

## Repository Structure

```text
├── data/           # O*NET and processed datasets
├── main.ipynb      # Analysis and simulation notebook
├── data_output/    # Qual output
└── data/           # Folder to store specific job tasks from the O*NET DB.
```

## Key Idea

Automation is not modelled as a simple binary replacement of labour. Instead, tasks can occupy different positions on a cognitive–physical complexity surface, allowing analysis of gradual and uneven technological diffusion across occupations.

## References

The study builds primarily on:

* Acemoglu & Restrepo (2018, 2019)
* Autor et al. (2003, 2024)
* Frey & Osborne (2017)
* Thompson et al. (2023)

## License

This repository is provided for research and educational purposes.