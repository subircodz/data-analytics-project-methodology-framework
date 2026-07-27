# Data Profiling

> **Document Type:** DAPM Phase 5

---

# Purpose

The Data Profiling phase examines the discovered datasets to understand their overall structure and condition.

The objective is to describe the characteristics of the raw data before any cleaning or validation begins.

Data Profiling identifies patterns, completeness, consistency, and potential data quality issues. It does not attempt to correct or validate the data.

---

# When to Use

Perform this phase after completing **Data Discovery**.

Data Profiling should always be completed before Data Cleaning.

---

# Profiling Overview

Provide a brief summary of the datasets examined during profiling.

Describe the overall condition of the data without suggesting any corrective actions.

---

# Dataset Summary

Document the basic characteristics of each dataset.

| Dataset | Records | Columns | File Size | Notes |
|----------|---------|---------|-----------|-------|
| | | | | |

---

# Column Summary

Provide a summary of the important columns in each dataset.

| Column | Data Type | Description |
|---------|-----------|-------------|
| | | |

---

# Missing Values

Document the missing values identified during profiling.

This section only reports the findings.

No cleaning decisions should be made here.

| Column | Missing Values | Percentage |
|---------|----------------|------------|
| | | |

---

# Duplicate Records

Document duplicate records identified during profiling.

| Dataset | Duplicate Records | Notes |
|----------|-------------------|-------|
| | | |

---

# Unique Values

Record the number of unique values for important columns where applicable.

| Column | Unique Values |
|---------|---------------|
| | |

---

# Value Distribution

Summarize how values are distributed within important columns.

Examples:

- Product Categories
- Order Status
- Customer Type
- Payment Method

| Column | Summary |
|---------|---------|
| | |

---

# Data Types

Verify the detected data type for important columns.

| Column | Expected Type | Detected Type |
|---------|---------------|---------------|
| | | |

---

# Potential Data Quality Issues

Record issues identified during profiling.

Examples:

- Missing values
- Duplicate records
- Blank fields
- Unexpected values
- Inconsistent formatting
- Mixed data types

Do not propose solutions in this section.

| Issue | Description |
|-------|-------------|
| | |

---

# Profiling Notes

Record any additional findings discovered during profiling.

Examples:

- Customer IDs appear to follow a consistent format.
- Date columns contain multiple formats.
- Product categories contain inconsistent spelling.
- Several optional fields are completely empty.

---

# Key Observations

Record factual observations identified during profiling.

Observations should describe the condition of the raw data without recommending corrective actions.

| Observation | Notes |
|-------------|-------|
| | |

---

# Phase Completion Summary

**Data Profiling is complete when:**

- Dataset structure has been documented.
- Record counts have been verified.
- Column information has been documented.
- Missing values have been identified.
- Duplicate records have been identified.
- Data types have been reviewed.
- Value distributions have been examined.
- Potential data quality issues have been documented.
- The project team has sufficient understanding to begin Data Cleaning.

---

# Next Step

Proceed to **Data Cleaning** to resolve the issues identified during Data Profiling and prepare the datasets for validation.

---

# Navigation

| Previous | Next |
|----------|------|
| [DATA_DISCOVERY](05_DATA_DISCOVERY.md) | [DATA_CLEANING](07_DATA_CLEANING.md) |