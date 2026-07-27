# Data Validation

> **Document Type:** DAPM Phase 7

---

# Purpose

The Data Validation phase verifies that the cleaned dataset satisfies the business rules and analytical requirements defined earlier in the project.

The objective is to confirm that the data is suitable for business analysis after cleaning has been completed.

Unlike Data Profiling, this phase does not examine the condition of the raw data. Instead, it verifies whether the cleaned data meets the expected business standards.

---

# When to Use

Perform this phase after completing **Data Cleaning**.

Data Validation should always be completed before Exploratory Data Analysis (EDA).

---

# Validation Overview

Provide a brief summary of the validation activities performed during this phase.

Describe what was validated and whether the dataset satisfies the required business rules.

---

# Validation Scope

Document the areas included in validation.

Examples:

- Business Identifier Validation
- Referential Integrity Validation
- Business Rule Validation
- Analytical Readiness Validation

---

# Business Identifier Validation

Verify that business identifiers satisfy the expected business rules.

Examples:

- Customer ID
- Product ID
- Order ID
- Employee ID

| Validation Rule | Status | Notes |
|-----------------|--------|-------|
| | Pass / Fail | |

---

# Referential Integrity Validation

Verify relationships between datasets.

Examples:

- Every Order belongs to a valid Customer.
- Every Product belongs to a valid Category.
- Every Employee belongs to an existing Department.

| Relationship | Status | Notes |
|--------------|--------|-------|
| | Pass / Fail | |

---

# Business Rule Validation

Verify that the dataset satisfies business-specific rules.

Examples:

- Quantity must be greater than zero.
- Revenue cannot be negative.
- Dispatch Date cannot be earlier than Order Date.
- Cancelled orders should not contribute to revenue.

| Business Rule | Status | Notes |
|---------------|--------|-------|
| | Pass / Fail | |

---

# Analytical Readiness

Confirm that the dataset is ready for analysis.

| Validation Check | Status |
|------------------|--------|
| Required datasets available | Pass / Fail |
| Required columns available | Pass / Fail |
| Business rules satisfied | Pass / Fail |
| Dataset ready for analysis | Pass / Fail |

---

# Validation Exceptions

Document any validation failures or unresolved issues.

| Validation | Issue | Impact |
|------------|-------|--------|
| | | |

---

# Validation Summary

Provide a summary of the overall validation outcome.

Example:

- All mandatory business rules passed.
- Two non-critical validation issues remain.
- Dataset approved for analysis.

---

# Key Observations

Record factual observations identified during Data Validation.

Observations should describe the validation results without drawing business conclusions.

| Observation | Notes |
|-------------|-------|
| | |

---

# Phase Completion Summary

**Data Validation is complete when:**

- Business identifiers have been validated.
- Dataset relationships have been verified.
- Business rules have been checked.
- Validation exceptions have been documented.
- The dataset has been confirmed as suitable for analysis.
- The project team has sufficient confidence to begin Exploratory Data Analysis.

---

# Next Step

Proceed to **EDA Report** to explore the validated dataset and answer the documented business questions.

---

# Navigation

| Previous | Next |
|----------|------|
| [DATA_CLEANING](07_DATA_CLEANING.md) | [EDA_REPORT](09_EDA_REPORT.md) |