

\# IPL Dataset - Initial Data Inspection



\## Dataset Overview

\- Total records: 577

\- Total columns: 17

\- Sheet name: cleaned\_matches



\## Data Quality Checks



\### 1. Missing Values

\- winner: 3 missing values

\- player\_of\_match: 3 missing values

\- Other columns: no missing values found



\### 2. Duplicate Records

\- Exact duplicate rows: 0



\### 3. Initial Observation

The records with missing winner and player\_of\_match

are associated with matches marked as "no result".



These missing values should be investigated before deciding

whether any cleaning is necessary.



\## Cleaning Decision

\- Preserve the original dataset.

\- Do not fill missing values with guesses.

\- Do not delete records without justification.

\- Perform additional validation before further analysis.



\## Status

Initial inspection completed.



