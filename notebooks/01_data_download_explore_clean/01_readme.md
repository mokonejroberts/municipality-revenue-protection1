# Data download, exploration, and cleaning.

## Overview.

This notebook performs initial data acquisition from Kaggle, followed by exploratory inspection and cleaning. It prepares raw CSV files for consolidation and downstream analysis. The workflow emphasizes traceability, data quality, and stakeholder-aligned formatting.

Referenced notebook: `01_data_download_explore_clean.ipynb`

## Inputs.

- Five raw CSV files sourced from Kaggle.

## Outputs.

- Cleaned individual datasets.
- Preliminary insights and data quality flags.

## Key modules.

- File loading and inspection.
- Missing value handling and imputation.
- Data type normalization.
- Initial anomaly detection and flagging.

## Stakeholder relevance.

This module ensures that raw data is ingested and cleaned in a reproducible, auditable manner. It sets the foundation for all downstream analysis and modeling. Cleaning logic is modular and documented for transparency.

## Notes.

All outputs are checkpointed for consolidation in `02_data_repackaging.ipynb`. Column naming conventions are aligned with stakeholder familiarity.

<!-- Minor edit to trigger GitHub preview update -->