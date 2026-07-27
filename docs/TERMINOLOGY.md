# DAPM Terminology

> **DAPM Version:** v0.2.1
> **Status:** Experimental
> **Document Type:** Terminology Standard

---

# Purpose

This document defines the standard terminology used throughout the Data Analytics Project Methodology (DAPM).

These definitions establish a common vocabulary for every DAPM project, ensuring that documents, templates, and discussions use consistent terminology.

Unless otherwise stated, the definitions in this document should be considered the official terminology of DAPM.

---

# Business Terms

## Business

An organization, client, department, or business domain for which an analytics solution is being developed.

---

## Business Problem

A business challenge or opportunity that requires analytical support to improve decision-making.

---

## Stakeholder

A person, department, or organization that uses the results of the analysis to make business decisions.

---

## Business Requirement

A business need that defines what information stakeholders require from the analytics project.

---

## Metric

A measurable value used to monitor business performance.

A metric describes performance but does not necessarily indicate success.

---

## Key Performance Indicator (KPI)

A metric directly linked to a business objective.

KPIs measure progress toward business goals.

---

# Project Terms

## Project Brief

A document defining the business problem, objectives, scope, assumptions, and project context before analytical work begins.

---

## Project Summary

A concise summary describing the completed analytics engagement, business problem, scope, major outcomes, and conclusion.

Unlike an Executive Summary, it documents the project rather than communicating results to business executives.

---

## Deliverable

A documented output produced by a DAPM phase.

Every phase should produce at least one deliverable.

---

# Data Terms

## Data Discovery

The process of identifying, locating, and understanding available data sources required for the project.

---

## Data Profiling

The process of examining the characteristics of the raw dataset before any modifications are made.

Typical profiling activities include:

- Record count
- Missing values
- Duplicate records
- Data types
- Null percentage
- Unique values
- Basic column statistics

Data Profiling describes the dataset.

It does not correct or validate the data.

---

## Data Cleaning

The process of correcting issues identified during Data Profiling.

Examples include:

- Removing duplicate records
- Handling missing values
- Standardizing formats
- Correcting data types

The objective is to produce a clean dataset suitable for validation.

---

## Data Validation

The process of verifying that the cleaned dataset satisfies defined business rules and analytical requirements.

Examples include:

- Business identifier validation
- Referential integrity validation
- Business rule validation
- Domain validation

Unlike Data Profiling, Data Validation produces a business outcome.

PASS

or

FAIL

---

# Analytics Terms

## Exploratory Data Analysis (EDA)

The process of exploring the cleaned and validated dataset to discover meaningful analytical patterns.

EDA focuses on exploration rather than data quality assessment.

---

## Observation

A factual statement describing what the data shows.

Observations should not explain why something happened.

---

## Business Insight

An interpretation explaining why one or more observations matter to the business.

Insights connect analytical findings with business understanding.

---

## Recommendation

A proposed business action supported by validated analytical evidence.

Recommendations should always be practical and evidence-based.

---

# Methodology Terms

## Framework

A structured system that defines how analytics projects should be executed.

DAPM is a framework.

---

## Methodology

A structured sequence of activities followed to complete an analytics project.

DAPM provides the methodology used throughout this framework.

---

## Architecture

The official workflow and phase responsibilities that define how DAPM operates.

---

## Principle

A governing rule that every DAPM project should follow.

---

## Philosophy

The beliefs and values that explain why DAPM exists.

---

## Validation Project

A practical analytics project used to evaluate and improve the methodology before introducing changes into a stable DAPM release.

---

# Reporting Terms

## Executive Summary

A concise document prepared for business decision-makers that summarizes the engagement, findings, and recommendations.

---

## Reporting

The process of communicating analytical findings through dashboards, reports, presentations, executive summaries, or other business deliverables.

---

# Relationship with Other Documents

This document defines the official terminology used throughout DAPM.

For the workflow, see **ARCHITECTURE.md**.

For the beliefs behind the methodology, see **PHILOSOPHY.md**.

For the rules governing every project, see **PRINCIPLES.md**.

---

**Document Version:** v0.2.0

**DAPM Version:** v0.2.0

**Status:** Under Validation