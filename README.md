# p-tau217–GFAP Discordance Score Calculator

This repository provides a research-use web calculator for the cohort-specific p-tau217–GFAP discordance score used in the CHASE and ADNI cohorts.

## Input scales

- **CHASE:** enter the original laboratory-reported plasma p-tau217 and GFAP concentrations in pg/mL. The calculator applies the log2 transformation internally. Do not pre-transform or Z-standardize the values.
- **ADNI:** enter the pTau-217 and GFAP NPQ values reported by the NULISA CNS Disease Panel. NPQ is already platform-normalized and expressed on a log2 scale. Do not enter pg/mL values or transform NPQ again.
- Enter age in years and select the baseline sex and diagnostic category as recorded.

The residual calculation and cohort-specific standardization are performed automatically.

## Intended use

This calculator is intended for research and method-reproduction purposes. It is not a clinical diagnostic or risk-prediction tool. The score is cohort- and platform-specific and should not be interpreted as a universal clinical threshold.

## Website

The calculator is available through GitHub Pages after publication of this repository.
