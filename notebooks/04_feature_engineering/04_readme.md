# Feature engineering.

## Overview.

This notebook creates modular features tailored for fraud detection and compliance analytics. It transforms raw and derived data into a structured feature set suitable for model development. All features are designed with interpretability and stakeholder alignment in mind.

## Inputs.

- Consolidated dataset from `02_data_repackaging.ipynb`.
- Insights from `03_exploratoty_data_analysis.ipynb`.

## Outputs.

- Engineered feature set.
- Feature documentation and completeness review.

## Key modules.

- Derived metrics and ratios.
- Temporal and categorical transformations.
- Missing value imputation.
- Feature selection and pruning.

## Stakeholder relevance.

Features are crafted to reflect operational realities and compliance signals. Each transformation is documented for auditability and interpretability. This module ensures that downstream models are built on transparent and reproducible inputs.

## Notes.

Feature engineering decisions are modular and traceable. All outputs are checkpointed for downstream modeling.
