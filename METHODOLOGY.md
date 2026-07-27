# DAPM Methodology

> **DAPM Version:** v0.2.1
>
> **Status:** Experimental

---

# What is DAPM?

The **Data Analytics Project Methodology (DAPM)** is a business-first framework for planning, executing, documenting, and delivering data analytics projects.

It provides a structured workflow that helps analysts understand the business problem before working with data.

DAPM combines business analysis, data analytics, and professional project documentation into a repeatable methodology.

The framework is designed to produce consistent, evidence-based analytics projects that can be understood by both technical and business stakeholders.

---

# Design Philosophy

DAPM is built on one simple principle:

> **Business First. Evidence Always.**

Every recommendation should be supported by evidence.

Every business insight should be supported by observations.

Every observation should be supported by validated data.

This ensures that conclusions are based on facts rather than assumptions.

---

# Project Modes

DAPM supports two ways of executing analytics projects.

---

## Consultant Mode

Use this mode when working with an organization or client.

The analyst interacts with stakeholders to understand the business problem and collect business requirements before beginning technical analysis.

Typical examples:

- Client projects
- Internal company analytics
- Consulting engagements

---

## Independent Project Mode

Use this mode when no client is available.

The analyst studies the available dataset, documentation, research papers, or public information to understand the business domain before beginning analysis.

Typical examples:

- Kaggle projects
- Portfolio projects
- Public datasets
- Academic case studies

Although the source of business understanding is different, the remaining DAPM workflow remains unchanged.

---

# DAPM Lifecycle

The methodology follows the sequence below.

```text
Project Brief
        ↓
Business Understanding
        ↓
Stakeholder Analysis
        ↓
Business Requirements
        ↓
Data Discovery
        ↓
Data Profiling
        ↓
Data Cleaning
        ↓
Data Validation
        ↓
EDA Report
        ↓
Business Insights
        ↓
Recommendations
        ↓
Executive Summary
```

---

# Phase Responsibilities

## Phase 1 – Project Brief

Defines the project scope, objectives, business problem, expected deliverables, and project boundaries.

---

## Phase 2 – Business Understanding

Develops an understanding of the business domain, operational workflow, business processes, and existing challenges.

---

## Phase 3 – Stakeholder Analysis

Identifies stakeholders, their responsibilities, decision-making roles, and reporting requirements.

---

## Phase 4 – Business Requirements

Captures business questions, required metrics, KPIs, dimensions, and reporting expectations.

---

## Phase 5 – Data Discovery

Identifies available data sources, datasets, ownership, formats, and accessibility.

---

## Phase 6 – Data Profiling

Examines the condition of the raw dataset.

Typical activities include:

- Record count
- Missing values
- Duplicate records
- Data types
- Null value analysis
- Basic statistics

The objective is to understand the dataset, not to validate it.

---

## Phase 7 – Data Cleaning

Improves data quality based on findings from Data Profiling.

Typical activities include:

- Removing duplicates
- Handling missing values
- Standardizing formats
- Correcting inconsistent values

The objective is to prepare clean data for validation.

---

## Phase 8 – Data Validation

Verifies that the cleaned dataset satisfies business requirements.

Typical activities include:

- Business identifier validation
- Referential integrity validation
- Business rule validation
- Domain validation

Unlike profiling, validation produces PASS or FAIL outcomes.

---

## Phase 9 – EDA Report

Explores the validated dataset to answer business questions.

EDA identifies:

- Patterns
- Trends
- Relationships
- Distributions
- Anomalies

EDA describes what the data shows.

---

## Phase 10 – Business Insights

Interprets analytical findings within the business context.

Business Insights explain what the findings mean for the organization.

---

## Phase 11 – Recommendations

Develops practical actions supported by business insights.

Recommendations should always be evidence-based.

---

## Phase 12 – Executive Summary

Summarizes the entire project for business stakeholders.

This document communicates the business problem, findings, recommendations, and expected business value.

---

# Supporting Artifacts

In addition to the primary phases, DAPM maintains supporting artifacts throughout the project.

| Artifact | Purpose |
|----------|---------|
| Project Journal | Records project discussions and implementation history. |
| Analytical Thinking | Captures assumptions, hypotheses, questions, and analytical reasoning. |
| Observations | Maintains a centralized register of factual observations. |
| Phase Checklist | Tracks project progress and completion status. |
| Project Summary | Provides a complete overview of the project for contributors and reviewers. |

---

# Evidence Flow

DAPM separates thinking, evidence, interpretation, and decision-making into different documents.

```text
Business Questions
        ↓
Analytical Thinking
        ↓
Validated Dataset
        ↓
EDA Findings
        ↓
Observations
        ↓
Business Insights
        ↓
Recommendations
        ↓
Executive Summary
```

This separation improves traceability and makes every business decision easier to justify.

---

# Guiding Principles

DAPM follows the following principles throughout every project.

- Understand the business before analysing data.
- Separate assumptions from evidence.
- Profile data before cleaning it.
- Validate data only after cleaning.
- Support every insight with evidence.
- Keep documentation clear and maintainable.
- Maintain traceability across all project phases.
- Build reusable project documentation.

---

# Who Should Use DAPM?

DAPM is suitable for:

- Data Analysts
- Business Analysts
- BI Developers
- Students
- Portfolio Builders
- Analytics Consultants

---

# Current Status

DAPM is currently under active validation through real-world analytics projects.

The methodology continues to evolve as new projects identify opportunities for improvement.

Future versions will incorporate practical lessons learned while maintaining the framework's core philosophy.

> **Business First. Evidence Always.**