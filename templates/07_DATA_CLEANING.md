# Data Cleaning

> **Document Type:** DAPM Phase 6

---

# Purpose

The Data Cleaning phase corrects the data quality issues identified during Data Profiling.

The objective is to improve the overall quality of the dataset by resolving missing values, duplicate records, inconsistent formatting, incorrect data types, and other data quality issues.

Data Cleaning prepares the dataset for business validation and analysis.

---

# When to Use

Perform this phase after completing **Data Profiling**.

Data Cleaning should always be completed before Data Validation.

---

# Cleaning Overview

Provide a brief summary of the cleaning activities performed during this phase.

Describe what was corrected without discussing business rule validation.

---

# Cleaning Strategy

Document the overall approach used to clean the data.

Examples:

- Remove duplicate records.
- Standardize text formatting.
- Convert data types.
- Handle missing values.
- Remove unnecessary columns.

---

# Cleaning Activities

Document every cleaning activity performed on the dataset.

| Issue Identified | Cleaning Action | Result |
|------------------|-----------------|--------|
| | | |

---

# Missing Value Handling

Document how missing values were handled.

Examples:

- Removed records
- Filled with default values
- Filled using business rules
- Left unchanged

| Column | Action Taken | Reason |
|---------|--------------|--------|
| | | |

---

# Duplicate Record Handling

Document how duplicate records were handled.

| Dataset | Action Taken | Records Affected |
|----------|--------------|------------------|
| | | |

---

# Data Type Corrections

Document any changes made to data types.

| Column | Original Type | Updated Type |
|---------|---------------|--------------|
| | | |

---

# Standardization

Document any formatting improvements made during cleaning.

Examples:

- Standardized date format.
- Converted text to proper case.
- Removed extra spaces.
- Standardized country names.

| Field | Standardization Applied |
|-------|--------------------------|
| | |

---

# Removed Data

Document any records or columns removed during cleaning.

| Item Removed | Reason |
|--------------|--------|
| | |

---

# Cleaning Summary

Provide a summary of the dataset after cleaning.

| Dataset | Records After Cleaning | Notes |
|----------|------------------------|-------|
| | | |

---

# Cleaning Notes

Record any important decisions made during the cleaning process.

Examples:

- Certain missing values were intentionally retained.
- Optional fields were not modified.
- Historical records were preserved.

---

# Key Observations

Record factual observations identified during Data Cleaning.

Observations should describe the work performed without confirming business correctness.

| Observation | Notes |
|-------------|-------|
| | |

---

# Phase Completion Summary

**Data Cleaning is complete when:**

- Missing values have been addressed where appropriate.
- Duplicate records have been handled.
- Data types have been corrected.
- Formatting has been standardized.
- Unnecessary records or columns have been removed.
- The dataset is ready for business validation.

---

# Next Step

Proceed to **Data Validation** to verify that the cleaned dataset satisfies the business rules and project requirements.

---

# Navigation

| Previous | Next |
|----------|------|
| [DATA_PROFILING](06_DATA_PROFILING.md) | [DATA_VALIDATION](08_DATA_VALIDATION.md) |