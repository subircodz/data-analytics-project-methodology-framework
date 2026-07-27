# DAPM Versioning

> **Document Type:** Versioning Policy

---

# Purpose

This document defines the versioning strategy followed by the Data Analytics Project Methodology (DAPM).

DAPM uses **Semantic Versioning** to communicate the scope and impact of every release.

Version numbers help users understand whether a release introduces major architectural changes, new functionality, or minor improvements.

---

# Version Format

DAPM versions follow the format:

```
MAJOR.MINOR.PATCH
```

Example:

```
v1.2.3
```

---

# Version Components

## Major Version

The **Major** version is incremented when the methodology undergoes significant architectural or structural changes that may affect existing projects or documentation.

Examples include:

- Workflow redesign
- Introduction or removal of project phases
- Breaking changes to the methodology
- Major template restructuring

---

## Minor Version

The **Minor** version is incremented when new functionality is introduced without changing the overall architecture.

Examples include:

- New project templates
- Additional documentation
- New checklists
- New principles
- New supporting artifacts

---

## Patch Version

The **Patch** version is incremented for improvements that do not introduce new functionality.

Examples include:

- Documentation improvements
- Typographical corrections
- Clarified terminology
- Template refinements
- Minor bug fixes

---

# Release Lifecycle

DAPM releases progress through the following stages.

| Status | Description |
|----------|-------------|
| Development | Active work is being carried out in the `develop` branch. Features may change frequently. |
| Under Validation | Changes are being evaluated through practical analytics projects before becoming part of a stable release. |
| Stable | The methodology has completed validation and is recommended for general use. |
| Deprecated | The version is retained for historical reference but is no longer maintained. |

---

# Current Version

| Property | Value |
|----------|-------|
| **DAPM Version** | v0.2.1 |
| **Status** | Experimental |

DAPM v0.2.0 represents the current development version of the methodology.

This release is being validated through multiple real-world analytics projects. Architectural decisions, templates, and documentation may continue to evolve based on implementation experience before the next stable release.

---

# Branch Strategy

DAPM follows a two-branch development model.

| Branch | Purpose |
|----------|---------|
| `develop` | Active development and experimentation. |
| `main` | Stable releases ready for public use. |

New features and methodology improvements are implemented and validated in the `develop` branch before being merged into `main`.

---

# Release Process

Every DAPM release follows the same workflow.

```
Development
        │
        ▼
Validation
        │
        ▼
Merge to main
        │
        ▼
Version Tag
        │
        ▼
GitHub Release
```

Only validated improvements are included in stable releases.

---

# Version History

| Version | Status | Notes |
|----------|--------|-------|
| v0.1.0 | Archived | Initial public methodology. |
| v0.1.1 | Archived | Documentation improvements and template refinements. |
| v0.2.0 | Under Validation | Architecture redesign introducing Data Profiling, revised workflow, and expanded project support. |