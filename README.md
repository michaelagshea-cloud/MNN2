# MNN5/YJL186W Dry-Lab Design Validation Repository

This repository organizes the current MNN5/YJL186W dry-lab design-validation evidence package.

## Current status

**MNN5 single-locus dry-lab design-validation package: strong.**  
**Wet-lab validation: not performed.**  
**Publication-level empirical predictive benchmark: not completed.**

The current MNN5 package supports a reproducible in-silico design record for the MNN5/YJL186W locus in a CEN.PK113-7D reference context. It includes sequence-model review, primer-gate review, full-genome mismatch-tolerant primer specificity screening, computational gRNA candidate selection, and scaffolds for external CRISPR scoring / empirical benchmarking.

## Strict claim boundary

Do not claim:

- wet-lab validation
- Sanger or amplicon sequencing confirmation
- edit experimentally installed
- humanized yeast chassis created
- EV phenotype validated
- publication-level empirical benchmark completed
- AUROC/PR-AUC achieved
- tool superiority over CRISPOR/CRISPRon/CRISPR-DIPOFF/etc.

## What is currently supported

- MNN5 in-silico sequence model consistency
- MNN5 primer thermodynamic review and redesign
- MNN5 full-genome mismatch-tolerant primer specificity screen under the current dry-lab standard
- MNN5 SpCas9/NGG gRNA candidate screen
- BioGRID ORCS yeast screen triage for gene-level phenotype/fitness context
- Benchmark scaffolds for future empirical CRISPR prediction benchmarking

## Repository map

```text
MNN5_single_locus_design/
  sequence_model/
  primer_validation/
  gRNA_design/
  external_scoring/

benchmark_crispr_prediction/
  data_manifests/
  scaffolds/
  ORCS_context/

docs/
  status/
  workflows/
  claim_boundaries/
  publication/

data/
  source_packages/
  current_final_packages/
  benchmark_scaffolds/
  quarantine_do_not_use/
```

## Recommended next steps

1. Push this repository to GitHub.
2. Run the CRISPR-DIPOFF wrapper locally with `MNN5_external_gRNA_scoring_input_package.zip`.
3. Run CRISPOR/CRISPRon external scoring and import results into the provided templates.
4. Curate true measured on-target activity rows from Doench/Azimuth or equivalent empirical datasets.
5. Only after real empirical rows exist, calculate AUROC, PR-AUC, Pearson/Spearman, RMSE, MAE, ranking metrics, and leakage checks.
6. Repeat the validated MNN5 gate for MNN2, then OCH1.

## Data note

Large raw external data and third-party source data should be cited and linked rather than redistributed if license terms are unclear.
