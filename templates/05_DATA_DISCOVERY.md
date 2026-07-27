# Data Discovery

> **Document Type:** DAPM Phase 4

---

# Purpose

The Data Discovery phase identifies, locates, and documents the data required to answer the business requirements.

The objective is to understand what data is available, where it is stored, who owns it, and whether it can be used for analysis.

This phase does **not** assess data quality. Data quality will be evaluated during the **Data Profiling** phase.

---

# When to Use

Perform this phase after completing **Business Requirements**.

Data Discovery should be completed before beginning Data Profiling.

---

# Data Discovery Overview

Provide a brief summary of the available data sources identified for the project.

This section should explain where the data comes from and how it supports the business requirements.

---

# Data Source Register

Document every dataset, system, or file identified during the discovery process.

| Data Source | Source Type | Owner | Description |
|-------------|-------------|-------|-------------|
| | Database / Excel / CSV / API / ERP / WMS / Other | | |

---

# Available Datasets

List the datasets that will be used during the project.

| Dataset | Purpose | Status |
|----------|---------|--------|
| | | Available / Pending |

---

# Available Tables or Files

If applicable, document the tables, worksheets, or files discovered during this phase.

| Name | Description |
|------|-------------|
| | |

---

# Data Availability

Document the availability of each data source.

| Data Source | Access Status | Notes |
|-------------|---------------|-------|
| | Available / Restricted / Pending | |

---

# Data Ownership

Identify who owns or maintains each data source.

| Data Source | Owner | Department |
|-------------|-------|------------|
| | | |

---

# Expected Data Relationships

Record any known relationships between datasets.

Examples:

- Orders linked to Customers
- Products linked to Categories
- Employees linked to Departments

| Related Datasets | Relationship |
|------------------|--------------|
| | |

---

# Known Limitations

Document any known limitations before profiling begins.

Examples:

- Historical data not available.
- Some datasets require additional approvals.
- Data extracted from multiple systems.
- Certain fields are confidential.

| Limitation | Business Impact |
|------------|-----------------|
| | |

---

# Discovery Notes

Record any important findings made while identifying the available data.

Examples:

- Multiple files exist for different years.
- Customer data comes from CRM.
- Inventory data is maintained in ERP.
- Sales data is received from external vendors.

---

# Key Observations

Record factual observations identified during Data Discovery.

Observations should describe what data exists without commenting on its quality.

| Observation | Notes |
|-------------|-------|
| | |

---

# Phase Completion Summary

**Data Discovery is complete when:**

- Required data sources have been identified.
- Available datasets have been documented.
- Data ownership has been recorded.
- Data availability is understood.
- Expected relationships between datasets have been identified.
- Known limitations have been documented.
- The project team has sufficient understanding to begin Data Profiling.

---

# Next Step

Proceed to **Data Profiling** to understand the structure, completeness, and overall condition of the discovered datasets.

---

# Navigation

| Previous | Next |
|----------|------|
| [BUSINESS_REQUIREMENTS](04_BUSINESS_REQUIREMENTS.md) | [DATA_PROFILING](06_DATA_PROFILING.md) |