# Claim Boundaries

## Supported now

| Claim | Status |
|---|---|
| MNN5/YJL186W in-silico sequence model has been assembled and checked | Supported by dry-lab files |
| MNN5 primer panel has passed current dry-lab primer-order gate | Supported under current in-silico standard |
| MNN5 guide candidates have been computationally selected | Supported as computational candidates |
| Yeast ORCS data provide gene-level context for MNN5/MNN2/OCH1 | Supported as gene-level context only |

## Not supported yet

| Claim | Status |
|---|---|
| Wet-lab validation | Not performed |
| Edit experimentally confirmed | Not performed |
| Sanger/amplicon/WGS confirmation | Not provided |
| Functional EV phenotype | Not provided |
| Humanized yeast chassis created | Not supported |
| Publication-level CRISPR benchmark completed | Not complete |
| AUROC/PR-AUC calculated | Not run |
| On-target Pearson/Spearman/RMSE/MAE calculated | Not run |
| Tool superiority demonstrated | Not run |

## Required evidence to upgrade claims

- Wet-lab PCR/Sanger/amplicon sequencing for edit confirmation
- Empirical activity datasets with guide-level measured activity
- Off-target empirical labels from GUIDE-seq/CIRCLE-seq/CHANGE-seq or equivalent
- Baseline tool outputs from CRISPOR/CRISPRon/CRISPR-DIPOFF/etc.
- Leakage-safe train/test splits
- Reproducible metric outputs with confidence intervals
