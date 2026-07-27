# DAPM Principles

> **DAPM Version:** v0.2.1  
> **Status:** Experimental
> **Document Type:** Engineering Principles

---

# Purpose

This document defines the principles that govern every project executed using the Data Analytics Project Methodology (DAPM).

These principles provide a common standard for analytical thinking, project execution, documentation, and decision-making.

Regardless of the project domain, dataset, or technology stack, every DAPM project should follow these principles.

---

# Principle 1 — Business First

Every analytics project shall begin with understanding the business problem before examining the available data or selecting technical tools.

The purpose of analytics is to solve business problems rather than produce technical outputs.

---

# Principle 2 — Stakeholder-Centric Thinking

Every project shall identify its stakeholders and understand the decisions they need to make.

Business questions, KPIs, metrics, insights, and recommendations should support stakeholder decision-making.

---

# Principle 3 — One Phase, One Responsibility

Every DAPM phase shall have one primary responsibility.

Activities serving different objectives should be placed in separate phases to keep the methodology simple, consistent, and maintainable.

---

# Principle 4 — Discover Early, Validate Later

Information may naturally emerge during any stage of the project.

Important findings should be documented immediately and validated within the appropriate DAPM phase instead of being ignored or postponed.

---

# Principle 5 — Profile Before Cleaning

The characteristics of the raw dataset shall be understood before any corrective action is taken.

Data Profiling identifies data quality issues.

Data Cleaning resolves those issues.

These activities should remain separate.

---

# Principle 6 — Clean Before Validation

Business validation shall be performed only after the dataset has been cleaned.

Validation should confirm that the data satisfies business expectations rather than identifying basic quality issues.

---

# Principle 7 — Evidence Before Recommendation

Every observation, business insight, and recommendation shall be supported by evidence obtained from the analysis.

Assumptions should never be presented as business conclusions.

---

# Principle 8 — Separate Observation from Insight

DAPM distinguishes between three levels of analytical thinking.

- **Observations** describe what the data shows.
- **Business Insights** explain why the observations matter.
- **Recommendations** define the actions that should be taken.

These deliverables serve different purposes and should never be combined.

---

# Principle 9 — Documentation as Deliverables

Documentation shall be developed throughout the project lifecycle.

Every DAPM phase should produce a documented deliverable that records decisions, findings, assumptions, and outcomes.

Documentation is considered part of the solution rather than an activity performed after implementation.

---

# Principle 10 — Technology Independence

DAPM shall remain independent of programming languages, databases, visualization tools, and analytics platforms.

The methodology should be equally applicable to projects implemented using spreadsheets, SQL, Python, R, Power BI, Tableau, or other technologies.

---

# Principle 11 — Continuous Validation

Changes to DAPM shall be introduced only after they have been validated through practical analytics projects.

Methodology improvements should be supported by evidence rather than theoretical assumptions.

---

# Principle 12 — Continuous Improvement

Every completed project should be treated as an opportunity to evaluate and improve the methodology.

Lessons learned during implementation should be documented and considered for future DAPM releases.

---

# Relationship with Other Documents

This document defines **how every DAPM project should be executed**.

For the beliefs and values behind the methodology, see **PHILOSOPHY.md**.

For the official workflow and phase responsibilities, see **ARCHITECTURE.md**.

---

**Document Version:** v0.2.0

**DAPM Version:** v0.2.0

**Status:** Under Validation