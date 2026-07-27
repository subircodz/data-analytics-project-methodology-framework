# DAPM Architecture

> **DAPM Version:** v0.2.1   
> **Status:** Experimental  
> **Document Type:** Architecture Specification

---

# Purpose

This document defines the official architecture of the **Data Analytics Project Methodology (DAPM)**.

It establishes the project workflow, the responsibility of each phase, and the design principles that govern the methodology.

Every DAPM project, template, and supporting document must follow the architecture defined here.

---

# Design Philosophy

DAPM is a **business-first** data analytics methodology.

The methodology separates business understanding from technical implementation and divides the analytics lifecycle into clearly defined phases.

Each phase has a single responsibility.

A phase should answer one primary question before the project proceeds to the next stage.

DAPM organizes information into logical phases. It does **not** restrict when information may be discovered. Information identified during one phase may be documented immediately and validated within its appropriate phase.

---

# DAPM Workflow

```text
Project Initiation
        │
        ▼
Business Understanding
        │
        ▼
Stakeholder Analysis
        │
        ▼
Business Requirements
        │
        ▼
Data Discovery
        │
        ▼
Data Profiling
        │
        ▼
Data Cleaning
        │
        ▼
Data Validation
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Business Insights
        │
        ▼
Recommendations
        │
        ▼
Executive Summary
```

---

# Phase Responsibilities

| Phase | Primary Question | Primary Deliverable |
|--------|------------------|---------------------|
| Project Initiation | What project are we undertaking? | Project Brief |
| Business Understanding | How does the business operate? | Business Understanding |
| Stakeholder Analysis | Who needs information? | Stakeholder Analysis |
| Business Requirements | What business questions must be answered? | Business Requirements |
| Data Discovery | What data is available? | Data Discovery |
| Data Profiling | What does the raw dataset look like? | Data Profiling Report |
| Data Cleaning | How should identified data issues be corrected? | Clean Dataset |
| Data Validation | Is the cleaned dataset suitable for analysis? | Validation Report |
| Exploratory Data Analysis | What patterns exist within the data? | EDA Report |
| Business Insights | What do the analytical findings mean? | Business Insights |
| Recommendations | What actions should be taken? | Recommendations |
| Executive Summary | What should management know? | Executive Summary |

---

# Phase Definitions

## 1. Project Initiation

Defines the scope and context of the analytics project before analytical work begins.

Typical project sources include:

- Client engagements
- Internal business initiatives
- Public datasets
- Kaggle projects
- Academic projects
- Research projects
- Personal practice projects

**Primary Deliverable**

- Project Brief

---

## 2. Business Understanding

Develops an understanding of the business domain before examining the data.

Typical activities include:

- Understanding business operations
- Identifying business problems
- Understanding business objectives
- Mapping operational workflows

Business Understanding focuses on the business rather than the available data.

---

## 3. Stakeholder Analysis

Identifies the individuals or departments involved in the business process.

Typical activities include:

- Identifying stakeholders
- Understanding responsibilities
- Understanding information needs
- Identifying decision makers

---

## 4. Business Requirements

Defines the analytical outcomes expected by the business.

Typical outputs include:

- Business questions
- KPIs
- Metrics
- Dimensions
- Reporting requirements

---

## 5. Data Discovery

Identifies all available datasets required for the project.

Typical sources include:

- Excel
- CSV
- SQL databases
- ERP systems
- CRM systems
- APIs
- Data warehouses
- Cloud storage

This phase inventories available data sources.

It does not assess data quality.

---

## 6. Data Profiling

Examines the characteristics of the raw dataset.

Typical activities include:

- Record count
- Missing values
- Duplicate records
- Data types
- Unique values
- Null percentage
- Basic column statistics

Data Profiling describes the condition of the dataset.

It does not determine whether the data satisfies business requirements.

---

## 7. Data Cleaning

Corrects issues identified during Data Profiling.

Typical activities include:

- Removing duplicate records
- Handling missing values
- Standardizing formats
- Correcting data types
- Cleaning inconsistent values

The output of this phase is a cleaned dataset.

---

## 8. Data Validation

Verifies that the cleaned dataset satisfies business requirements.

Typical validation activities include:

- Business identifier validation
- Referential integrity validation
- Business rule validation
- Domain validation

Unlike Data Profiling, Data Validation produces a clear business outcome.

**PASS**

or

**FAIL**

---

## 9. Exploratory Data Analysis (EDA)

Explores the cleaned and validated dataset to identify meaningful patterns.

Typical activities include:

- Trend analysis
- Distribution analysis
- Correlation analysis
- Outlier identification
- Segmentation

EDA focuses on business exploration rather than data quality assessment.

---

## 10. Business Insights

Transforms analytical findings into business knowledge.

Insights explain:

- What happened
- Why it happened
- Why it matters to the business

---

## 11. Recommendations

Provides practical, evidence-based actions derived from validated business insights.

Recommendations should always be supported by analytical evidence.

---

## 12. Executive Summary

Provides a concise summary for business decision makers.

Typical contents include:

- Business problem
- Scope of analysis
- Key findings
- Business insights
- Recommended actions

The Executive Summary should allow management to understand the engagement without reviewing the complete project documentation.

---

# Design Principles

## Business First

Business understanding always precedes technical implementation.

---

## One Phase, One Responsibility

Each phase exists to answer one primary question.

Activities should not overlap unnecessarily.

---

## Discover Early, Validate Later

Information may naturally emerge during any project activity.

DAPM organizes and validates information within the appropriate phase rather than restricting when it may be discovered.

---

## Separate Profiling from Validation

Data Profiling describes the characteristics of the dataset.

Data Validation verifies business correctness.

These activities serve different purposes and should remain independent.

---

## Evidence Before Recommendation

Recommendations should always be supported by validated analytical findings.

---

## Documentation Before Implementation

Project documentation should be completed progressively throughout the engagement.

Documentation is considered a project deliverable rather than an afterthought.

---

# Architecture Decisions

| ID | Decision | Status |
|----|----------|--------|
| ADR-001 | Separate Data Profiling from Data Validation | Accepted |
| ADR-002 | Introduce Project Initiation as the first phase to support consultant, academic, and self-learning projects | Accepted |
| ADR-003 | Assign a single responsibility to every DAPM phase | Accepted |
| ADR-004 | Allow information discovery in any phase while validating it within the appropriate phase | Accepted |

---

# Validation Status

DAPM v0.2 is currently under validation.

The architecture will continue to be validated through practical analytics projects before being released as a stable version.

Current validation projects include:

- Warehouse Operations & Inventory Analytics
- Distribution Center & Logistics Analytics
- WAVE (Warehouse Analytics Validation Engine)

---

# Version History

| Version | Description |
|---------|-------------|
| v0.1 | Initial methodology |
| v0.1.1 | Documentation improvements and template validation |
| v0.2 | Architecture redesign introducing Project Initiation, Data Profiling, and revised phase responsibilities |