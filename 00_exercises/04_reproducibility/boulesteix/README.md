# Reproduction of Boulesteix et al. (2020)

<!-- badges: start -->
<!-- badges: end -->

Reproducible version of the simulation study in Boulesteix et al. (2020), "Introduction to statistical simulations in health research", for the course MLaRPiS.

Klaas Dieleman, Nov 2026.

## Software

| Component | Version |
|-----------|---------|
| R | 4.5.2 |
| Quarto | 1.11.9 |

## Contents

- `boulesteix.qmd`: the reproducible research manuscript (code and results)
- `scripts/original_script.R`: the original script from the paper, unmodified
- `data/`: input data (downloaded from [CDC - NHANES](https://wwwn.cdc.gov/nchs/nhanes/continuousnhanes/default.aspx?BeginYear=2015))

## Instructions

Use [renv](https://rstudio.github.io/renv/), from this folder, to install correct packages and versions. Then render `boulesteix.qmd` using Quarto.