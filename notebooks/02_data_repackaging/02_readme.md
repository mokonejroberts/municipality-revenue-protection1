# Data repackaging.

## Overview.

This notebook consolidates multiple cleaned datasets into a unified format suitable for downstream analysis. It applies structured merge and combine techniques to produce a single full dataset, ensuring consistency and traceability across all records.

## Inputs.

- Five cleaned individual datasets from `01_data_download_explore_clean.ipynb`.

## Outputs.

- Consolidated dataset for exploratory analysis and feature engineering.

## Key modules.

- Dataset alignment and merge logic.
- Column standardization and renaming.
- Integrity checks and duplication handling.
- Export of unified dataset for downstream use.

## Stakeholder relevance.

This module ensures that all data sources are harmonized into a single, auditable structure. It supports transparency in how raw inputs are transformed into analysis-ready formats. The resulting dataset is the foundation for all subsequent modeling and diagnostics.

## Notes.

Merge logic is modular and traceable. Column naming conventions are aligned with stakeholder familiarity. All outputs are checkpointed for reproducibility.
