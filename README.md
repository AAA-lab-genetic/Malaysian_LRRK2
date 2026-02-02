# Malaysian_LRRK2

`GP2 ❤️ Open Science 😍`



## Summary
This is the online repository for the manuscript titled "LRRK2 mutation spectrum and association study in a multi-ethnic cohort of Malaysian Parkinson’s Disease patients". This study aims to XXX

## Data Statement
- All GP2 data are hosted in collaboration with the Accelerating Medicines Partnership in Parkinson's Disease and are available via application on the website. The GP2 PD case and control data are available via the GP2 website (https://gp2.org; release 11: [https://doi.org/10.5281/zenodo.10472143](https://zenodo.org/records/14510099)). Genotyping imputation, quality control, ancestry prediction, and processing were performed using GenoTools (v1.0.0), publicly available on GitHub

# Repository Orientation
```
THIS_REPO
└── README.md
└── analysis
  └── 01_PC_selection.ipynb 
  ├── 02_annotation.ipynb   
  └── 03_assoc.ipynb  
  └── 04_burden_and_kernel_test.ipynb
  └── 05_haplotype_analysis.ipynb  
  └── 06_concordance_check.ipynb


```

## Notebooks Description
- Languages: Python, bash, and R

|Directory| Notebook                                 |Description                                                 |
|:--------|:-----------------------------------------|:-----------------------------------------------------------|
|analysis/     | 01_PC_selection.ipynb                    | Selecting number of PCs for association study                          | 
|         | 02_annotation.ipynb                      | Annotating data with annovar           | 
|         | 03_assoc.ipynb                           | Running association for all variants      |
|         | 04_burden_and_kernel_test.ipynb          | Running rare variant burden and kernel test |
|         | 05_haplotype_analysis.ipynb              | Generate haplotype and run haplotype association for LRRK2 gene     |
|         | 06_concordance_check.ipynb               | Checking the concordance of variant genotype between the sequencing technology  |

# Software
|       **Software**                | **Version(s)** |           **Resource URL**                                           |   **RRID**     |                                                               **Notes**                                               |
|:---------------------------------:|:--------------:|:--------------------------------------------------------------------:|:--------------:|:---------------------------------------------------------------------------------------------------------------------:|
| Python Programming Language       |3.10            |http://www.python.org/                                                | RRID:SCR_008394| pandas; numpy; seaborn; matplotlib; statsmodel; rpy2; used for general data wrangling/plotting/analyses                     |
|R Project for Statistical Computing|4.4.2           |http://www.r-project.org/                                             | RRID:SCR_001905| tidyverse; dplyr; tidyr; ggplot2; car; cowplot; grid; RColorBrewer; forestmodel; survival; used for general data wrangling/plotting/analyses|
|PLINK                              |1.9 and 2.0     |http://www.nitrc.org/projects/plink                                   | RRID:SCR_001757| used for genetic analyses                                                                                             |
|RVtest |4.4.2           |http://www.r-project.org/                                             | RRID:SCR_001905| tidyverse; dplyr; tidyr; ggplot2; car; cowplot; grid; RColorBrewer; forestmodel; survival; used for general data wrangling/plotting/analyses|
|ANNOVAR |4.4.2           |http://www.r-project.org/                                             | RRID:SCR_001905| tidyverse; dplyr; tidyr; ggplot2; car; cowplot; grid; RColorBrewer; forestmodel; survival; used for general data wrangling/plotting/analyses|




