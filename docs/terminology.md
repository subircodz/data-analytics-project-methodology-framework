# DAPM Terminology

## Purpose

This document defines the terminology used throughout the Data Analytics Project Methodology (DAPM).

Consistent terminology reduces ambiguity, improves communication, and ensures that every phase of the methodology is interpreted consistently across projects.

Unless otherwise stated, the definitions in this document should be considered the standard terminology for all projects following DAPM.

---

# Business

An organization, client, or domain for which a data analytics solution is being developed.

Examples include retail stores, hospitals, warehouses, financial institutions, educational organizations, and manufacturing companies.

---

# Business Problem

A challenge or opportunity that requires analytical support to improve decision-making.

Example:

A warehouse frequently experiences stock shortages despite maintaining high inventory levels.

---

# Stakeholder

A person or group that uses the results of the analysis to make business decisions.

Examples:

- CEO
- Warehouse Manager
- Sales Manager
- Finance Manager
- HR Manager

---

# Business Requirement

A business need that the analytics project is expected to address.

Business requirements define what information stakeholders need in order to make informed decisions.

---

# Metric

A measurable value used to monitor business performance.

Examples:

- Revenue
- Number of Orders
- Inventory Level
- Employee Attendance

Metrics describe performance but do not necessarily indicate success.

---

# Key Performance Indicator (KPI)

A metric that is directly linked to a business objective.

KPIs measure whether important business goals are being achieved.

Example:

Reducing order delivery time from 5 days to 3 days.

---

# Data Discovery

The process of identifying, locating, and collecting data required for the project.

Data may originate from spreadsheets, databases, APIs, ERP systems, CRM platforms, CSV files, or other business systems.

---

# Data Validation

The process of assessing whether collected data is accurate, complete, consistent, and suitable for analysis.

Validation identifies issues but does not correct them.

Examples:

- Missing values
- Duplicate records
- Invalid dates
- Incorrect data types
- Impossible values

---

# Data Cleaning

The process of correcting or handling issues identified during data validation.

Examples:

- Removing duplicates
- Standardizing text
- Converting data types
- Handling missing values

The objective is to produce an analysis-ready dataset.

---

# Exploratory Data Analysis (EDA)

The process of exploring and understanding the data after it has been validated and cleaned.

EDA focuses on discovering patterns, distributions, trends, relationships, and anomalies without drawing business conclusions.

EDA includes:

- Analysis
- Visualization
- Recording observations

---

# Observation

A factual statement describing what the data shows.

Observations should be objective and supported directly by the data.

Example:

Electronics accounted for 42% of all product returns.

Observations do not explain why something happened.

---

# Business Insight

A meaningful interpretation of one or more observations within a business context.

Insights explain what observations mean for the business and help answer stakeholder questions.

Business insights are developed by connecting observations with business knowledge, domain understanding, and stakeholder objectives.

Example:

A significant proportion of returns originate from products supplied by Supplier A, suggesting a potential quality concern.

---

# Recommendation

A proposed business action supported by business insights.

Recommendations should be practical, evidence-based, and aligned with stakeholder objectives.

Example:

Conduct a quality audit of Supplier A and establish a secondary supplier to reduce operational risk.

---

# Reporting

The process of communicating findings to stakeholders.

Reporting may include dashboards, presentations, PDF reports, executive summaries, or portfolio documentation.

Reporting communicates insights and recommendations but does not create them.

---

# Deliverable

A tangible output produced at the completion of a project phase.

Examples:

- Validation Report
- Clean Dataset
- EDA Report
- Business Insights Report
- Executive Report

Every DAPM phase should produce at least one unique deliverable.

---

# Methodology

A structured, repeatable approach for executing data analytics projects from business understanding through reporting.

DAPM provides the methodology used throughout this repository.

---

**Document Version:** v0.1.1  
**DAPM Version:** v0.1.1  
**Status:** Experimental