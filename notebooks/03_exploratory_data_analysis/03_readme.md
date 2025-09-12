# Exploratory data analysis.

## Overview.

This notebook performs statistical and visual exploration of the consolidated dataset. It surfaces patterns, anomalies, and correlations relevant to fraud detection and billing irregularities. The insights generated here inform feature engineering and model design.

## Inputs.

- Consolidated dataset from `02_data_repackaging.ipynb`.

## Outputs.

- Summary statistics and distribution plots.
- Correlation matrices and anomaly flags.
- Feature relevance insights for engineering.

## Key modules.

- Descriptive statistics and data profiling.
- Distribution analysis across key variables.
- Correlation mapping.
- Outlier detection and anomaly surfacing.

## Stakeholder relevance.

This module helps stakeholders understand the underlying structure and behavior of the data. It identifies potential fraud signals and informs which features are most relevant for downstream modeling. Visuals are annotated for clarity and auditability.

## Notes.

Multicollinearity analysis and heatmaps are planned but not yet implemented. This section will be updated once the notebook is revised.  
Findings from this notebook directly influence the logic and scope of `04_feature_engineering.ipynb`. All plots and summaries are checkpointed for reproducibility.
