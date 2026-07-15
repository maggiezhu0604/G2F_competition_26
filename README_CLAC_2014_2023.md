# CLAC 2014-2023 aligned data

This directory is a derived, CLAC-compatible run layout.

- Training source: `/Users/maggiezhu/Documents/2022 Gx Fdata/2024 competation/Training_data`
- Testing source: `/Users/maggiezhu/Documents/2022 Gx Fdata/2024 competation/Testing_data`
- CLAC-compatible training directory: `Training_Data/`
- CLAC-compatible testing directory: `Testing_Data/`
- Compatibility copy for local smoke-test scripts: `Testing/submission_template.csv`

The original CLAC script expects filenames ending in `2014_2021` and `2022`.
Those filenames are preserved here so the original code can run with minimal
changes, but the file contents come from the 2014-2023 training set and 2024
testing set.

Use:

```r
setwd("/Users/maggiezhu/Documents/2022 Gx Fdata/runs/clac_2014_2023_aligned")
source("Script_CLAC_model_2014_2023_aligned.R")
```

Important QA outputs are under `alignment_report/`.
