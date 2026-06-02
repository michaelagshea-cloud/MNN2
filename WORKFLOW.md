# Workflow

## MNN5 single-locus design-validation workflow

1. Sequence model integrity check
2. ORF/translation check
3. Cassette/homology-arm boundary check
4. Primer3 thermodynamic screening
5. Full-genome mismatch-tolerant primer specificity screen
6. gRNA candidate selection
7. Whole-genome guide off-target candidate screen
8. Donor/edited recutting-risk screen
9. External guide scoring import
10. Claim-boundary review
11. Reproducible ZIP + manifest

## Benchmark workflow

1. Lock independent empirical datasets
2. Standardize off-target data
3. Standardize on-target activity data
4. Generate your method predictions
5. Generate baseline tool predictions
6. Freeze train/test splits
7. Run leakage checks
8. Compute AUROC, PR-AUC, recall at fixed FPR
9. Compute Pearson/Spearman/RMSE/MAE
10. Compute ranking and robustness metrics
11. Report confidence intervals
12. Write data/code availability statements
