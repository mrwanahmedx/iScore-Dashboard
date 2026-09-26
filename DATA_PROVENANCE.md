# Data Provenance and Confidentiality Audit

## Dataset

This historical Tableau portfolio project uses `credit_risk_dataset.csv`, the public **Credit Risk Dataset** published by Lao Tse on Kaggle.

- Source: https://www.kaggle.com/laotse/credit-risk-dataset
- License shown by the source: **CC0: Public Domain**
- Public schema includes `person_age`, `person_income`, `person_home_ownership`, `person_emp_length`, `loan_intent`, `loan_grade`, `loan_amnt`, `loan_int_rate`, `loan_status`, `loan_percent_income`, `cb_person_default_on_file`, and `cb_person_cred_hist_length`.

## Packaged-workbook audit

On 2026-09-26 the public `iScore.twbx` package was inspected at the metadata/schema level.

The package contains:
- one Tableau workbook definition,
- two embedded Tableau Hyper extracts,
- image assets.

The workbook datasource metadata identifies `credit_risk_dataset.csv` and exposes the same public field family listed above. No private employer file path, corporate SharePoint/OneDrive path, corporate email field, national-ID field, or employer-specific internal table identifier was found in the workbook metadata audit.

This audit does **not** convert the project into a production credit model. It remains a descriptive legacy portfolio dashboard.

## Boundary

The historical repository name does not imply employer or bureau affiliation. Do not add employer/customer data, internal screenshots, proprietary schemas, internal model outputs, credentials, or private financial information to this repository.
