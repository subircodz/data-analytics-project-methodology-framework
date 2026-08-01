# Data Analytics Project Methodology (DAPM)

> **Version:** v0.2.1  
> **Status:** Experimental

---

> **Archive Notice**
>
> This document represents the DAPM v0.2.1 methodology used during the initial validation phase.
>
> For the latest methodology, refer to **METHODOLOGY.md**.

# Overview

The **Data Analytics Project Methodology (DAPM)** is a structured, business-first framework for planning, executing, documenting, and delivering professional data analytics projects.

Rather than treating analytics as dashboard development, DAPM views analytics as a systematic process of understanding business problems, validating data, producing evidence, and communicating actionable recommendations.

The methodology integrates business analysis, data analytics, engineering practices, and project documentation into a repeatable workflow that promotes consistency, transparency, and traceability throughout the project lifecycle.

---

# Philosophy

DAPM is founded on a simple principle:

> **Business First. Evidence Always.**

Every stage of the methodology supports this principle.

- Business problems drive analytical work.
- Data supports observations.
- Observations support insights.
- Insights support recommendations.
- Recommendations create business value.

The methodology encourages analysts to base decisions on validated evidence rather than assumptions or intuition.

---

# Core Principles

DAPM follows these principles throughout every project.

## Business Before Data

Understand the business domain before analysing the dataset. Technology exists to solve business problems, not the other way around.

---

## Evidence Before Conclusions

Every analytical conclusion should be supported by evidence.

Separate assumptions, observations, insights, and recommendations into dedicated project artefacts.

---

## Phase Isolation

Each phase has a single responsibility.

A phase should complete its intended objective before progressing to the next stage.

For example:

- Profiling discovers the condition of the data.
- Preparation improves data quality.
- Validation verifies business correctness.
- EDA discovers analytical patterns.

Each phase answers a different question.

---

## Engineering Judgement

DAPM distinguishes between **business deliverables** and **engineering improvements**.

Activities such as memory optimisation, datatype optimisation, execution tuning, caching, or performance enhancement should only be introduced when they provide measurable value, such as recurring analytical workflows or production data pipelines.

Avoid premature optimisation in one-time analytical projects.

---

## Documentation as a Deliverable

Documentation is considered part of the final deliverable rather than an optional activity.

Every significant decision, observation, and analytical conclusion should be documented throughout the project.

---

# Project Execution Modes

DAPM supports two execution modes.

## Consultant Mode

Use this mode when working directly with business stakeholders.

The analyst gathers business requirements through meetings, workshops, interviews, and organisational documentation before beginning technical analysis.

Typical projects include:

- Client engagements
- Internal business analytics
- Consulting projects

---

## Independent Project Mode

Use this mode when stakeholders are unavailable.

Business understanding is developed from publicly available information such as documentation, reports, research papers, domain knowledge, or dataset descriptions.

Typical projects include:

- Portfolio projects
- Kaggle competitions
- Public datasets
- Academic case studies

Although the source of business understanding differs, the remaining DAPM workflow remains unchanged.

---

# DAPM Lifecycle

```text
Project Brief
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
Data Preparation
        │
        ▼
Data Validation
        │
        ▼
Exploratory Data Analysis
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

## Phase 1 — Project Brief

Defines the project scope, objectives, expected deliverables, assumptions, constraints, and success criteria.

---

## Phase 2 — Business Understanding

Develops a clear understanding of the business domain, operational processes, organisational objectives, and current business challenges.

---

## Phase 3 — Stakeholder Analysis

Identifies business stakeholders, their responsibilities, decision-making authority, reporting requirements, and expectations.

---

## Phase 4 — Business Requirements

Defines business questions, KPIs, dimensions, required reports, and analytical objectives.

These requirements guide the entire analytical workflow.

---

## Phase 5 — Data Discovery

Identifies available data sources, datasets, ownership, formats, accessibility, and business relevance.

---

## Phase 6 — Data Profiling

Examines the condition of the raw dataset.

Typical profiling activities include:

- Worksheet discovery
- Record counts
- Column discovery
- Datatype profiling
- Missing value profiling
- Duplicate detection
- Unique value analysis

The objective of profiling is **to understand the dataset**, not to modify or validate it.

---

## Phase 7 — Data Preparation

Improves dataset quality based on profiling findings.

Typical preparation activities include:

- Handling missing values
- Removing duplicates
- Standardising formats
- Correcting inconsistencies
- Preparing analytical datasets

The objective is to produce clean, analysis-ready data.

---

## Phase 8 — Data Validation

Verifies that the prepared dataset satisfies business expectations.

Typical validation activities include:

- Business identifier validation
- Referential integrity validation
- Business rule validation
- Domain validation

Unlike profiling, validation produces measurable PASS or FAIL outcomes.

---

## Phase 9 — Exploratory Data Analysis

Explores the validated dataset to identify patterns, trends, distributions, relationships, and anomalies.

EDA answers:

> **What does the data tell us?**

---

## Phase 10 — Business Insights

Interprets analytical findings within the business context.

Insights explain the significance of the analytical results and their impact on business operations.

---

## Phase 11 — Recommendations

Transforms validated insights into practical, evidence-based business actions.

Recommendations should always be supported by analytical findings.

---

## Phase 12 — Executive Summary

Communicates the complete project to business stakeholders using concise, non-technical language.

---

# Supporting Artefacts

DAPM maintains several supporting artefacts throughout the project lifecycle.

| Artefact | Purpose |
|----------|---------|
| Project Journal | Records project activities, implementation decisions, and development history. |
| Analytical Thinking Register | Documents assumptions, hypotheses, engineering decisions, and analytical reasoning. |
| Observation Register | Maintains verified observations collected throughout the project. |
| Phase Checklist | Tracks completion status for every DAPM phase. |
| Project Summary | Provides a consolidated overview of the completed project. |

---

# Evidence Flow

DAPM separates thinking, evidence, interpretation, and decision-making into dedicated artefacts.

```text
Business Questions
        │
        ▼
Analytical Thinking
        │
        ▼
Data Profiling
        │
        ▼
Data Preparation
        │
        ▼
Data Validation
        │
        ▼
Verified Observations
        │
        ▼
Exploratory Data Analysis
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

This separation improves traceability, simplifies reviews, and ensures every recommendation can be traced back to validated evidence.

---

# Intended Audience

DAPM is suitable for:

- Data Analysts
- Business Analysts
- BI Developers
- Analytics Engineers
- Students
- Portfolio Builders
- Analytics Consultants

---

# Current Status

DAPM is currently being validated through real-world analytics projects and continues to evolve based on practical engineering experience.

Each completed project contributes refinements to the methodology while preserving its core philosophy.

> **Business First. Evidence Always.**