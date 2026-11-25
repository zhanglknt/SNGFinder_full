# Supplementary numbering in this repository (v9.13 sync)

The manuscript (NAR submission **v9.13, 2026-11-25**) numbers its
supplementary tables **S1–S28** and supplementary figures **S1–S25**.
Repository scripts, data filenames and some shorthand labels keep their
original v9.0 numbering; anchored prose references have been rewritten.

Paper title: *A systematic dissection of new-gene origination, turnover and function across the AA-genome Oryza species*

## What was synced (v9.9 -> v9.13)

- Anchored prose references ("Table S5", "Supplementary Tables S3 and S10", …)
  rewritten to the v9.13 numbering using the table below.
- **Not renamed**: file names, directory names, output artifact names,
  variable names and Excel sheet names. They are part of the executable
  reproduction chain. Examples: `scripts/table_S4/`, `scripts/rate_window_S23.py`,
  `classifier_data/ablation_orphan_calls/S13_unified.tsv`,
  `verify_vs_S12.tsv`, `S24_oryza_clade_strata`.
- **Figure references unchanged**: supplementary figures are S1–S25 in both
  v9.9 and v9.13.
- The published Zenodo data bundle 10.5281/zenodo.24130664 keeps its original
  title "SNGFinder Table S4 reproduction data bundle"; published records
  cannot be edited. That table is Supplementary Table **S4** in v9.13
  (it was S2 in v9.9).

## Note on one-to-many mappings

v9.9 had 22 merged tables; v9.13 has 28 single-sheet tables. Where one v9.9
table split into several v9.13 tables, prose was resolved by content:

| v9.9 | v9.13 | resolution |
|---|---|---|
| S5  | S7 (+ S12) | every prose mention is the **ablation** table (S12 is the per-fold metric sheet, never referenced in prose) |
| S10 | S13 | orphan feature values — **KEY-JOINed** with classifier output |
| S14 | S13 | XGBoost classification results — **KEY-JOINed** with the above |
| S1  | S1, S2, S3 | not referenced in prose |
| S17 | S19, S20 | not referenced in prose |
| S18 | S21, S22 | not referenced in prose |
| S20 | S24, S25 | not referenced in prose |
| S22 | S27, S28 | not referenced in prose |

## v9.9 -> v9.13 : supplementary TABLES

| v9.9 | v9.13 | used in prose | note |
|---|---|---|---|
| S1 | S1, S2, S3 | — | split |
| S2 | S4 | S4 |  |
| S3 | S5 | S5 |  |
| S4 | S6 | S6 |  |
| S5 | S7, S12 | S7 | split |
| S6 | S8 | S8 |  |
| S7 | S9 | S9 |  |
| S8 | S10 | S10 |  |
| S9 | S11 | S11 |  |
| S10 | S13 | S13 |  |
| S11 | S14 | S14 |  |
| S12 | S15 | S15 |  |
| S13 | S16 | S16 |  |
| S14 | S13 | S13 |  |
| S15 | S17 | S17 |  |
| S16 | S18 | S18 |  |
| S17 | S19, S20 | — | split |
| S18 | S21, S22 | — | split |
| S19 | S23 | S23 |  |
| S20 | S24, S25 | — | split |
| S21 | S26 | S26 |  |
| S22 | S27, S28 | — | split |

Figures: unchanged (S1–S25 in both versions).

Generated from `v910_plan.json::map_v99_to_v910` (authoritative) by
`tmp_nar1109/sync_repo_v913.py`.
