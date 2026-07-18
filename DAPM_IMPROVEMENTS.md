## Observation 001

**Project:**
Warehouse Operations & Inventory Analytics

**Proposed Improvements:**
- A separate Observation Journal significantly improved traceability.
- A seperate Projet Brief, made the case look like real.
- Introduce a separate ANALYTICAL_THINKING.md document to capture initial analytical ideas after Business Understanding.
- Keep the document lightweight and implementation-independent.

**Evidence:**
Observed during Phase 1.

**Action:**
Implemented.

**Status:**
Validated ✅

---

## Observation 002

**Project:**
Warehouse Operations & Inventory Analytics

**Proposed Improvement:**
Introduce a lightweight `PHASE_CHECKLIST.md` to define completion criteria for each phase.

**Evidence:**
Observed during transition from Phase 1 to Phase 2.

**Action:**
Implemented.

**Status:**
Validated ✅

---

## Observation 003

**Project:**
Customer Registration System 

**Proposed Improvement:**
Methodology Rule Never introduce stakeholders, business processes, or organizational roles that have not been explicitly identified by the client or validated during the project.

**Business-Driven Column Selection**  
After the Business Understanding phase and before Data Cleaning & Preparation.
Purpose

**Before loading or cleaning data, identify:**

    • Which tables are required?   
    • Which columns are required?   
    • Which columns are irrelevant to the current business question?   

**Benefit**

Instead of cleaning every column:
```
Raw Dataset
      │
      ▼
Clean Everything ❌

We move to:

Business Question
      │
      ▼
Identify Required Columns
      │
      ▼
Load Only Those Columns
      │
      ▼
Clean Only Those Columns
      │
      ▼
Analysis

This leads to:
    • Faster analysis   
    • Lower memory usage   
    • Simpler code   
    • Less unnecessary cleaning   
    • Better alignment with the business objective  
```


**Evidence:**
Observed during project completion

**Action:**
Re-evaluate after Project 5.

**Status:**
🟡 Pending validation.

---

## Observation 004

**Project:**
Warehouse Operations & Inventory Analytics

**Proposed Improvement:**
Introduce a lightweight `PHASE_DELIVERABLES.md` (or an equivalent knowledge handover artifact) to formally capture the validated outputs of each DAPM phase. These outputs would become the primary input for the subsequent phase, establishing an explicit knowledge pipeline throughout the methodology.

**Evidence:**
During the transition from Business Understanding to Stakeholder Analysis, information had to be interpreted from multiple project documents (Project Brief, Project Case Journal, Observations, and Analytical Thinking). There was no single authoritative artifact representing the official outputs of the completed phase.

**Action:**
Observe the transition between every DAPM phase across at least five validation projects. Introduce the artifact only if the same gap consistently appears.

**Status:**
🟡 Pending validation.

---

## Observation 005

**Project:**
Distribution Center & Logistics Analytics

**Proposed Improvement:**
Add a guiding principle to DAPM clarifying that the phases represent analytical activities rather than isolated meetings. Information relevant to later phases may naturally emerge during earlier client discussions and should be captured immediately, then validated during the appropriate DAPM phase.

**Evidence:**
During the Stakeholder Analysis phase, the client naturally revealed several business requirements and potential KPIs while discussing stakeholder information needs. The current methodology does not explicitly explain whether such information should be deferred until the corresponding phase or documented immediately. This created uncertainty during the validation project, despite the information being valuable and relevant.

**Action:**
Observe future validation projects to determine whether information consistently overlaps across DAPM phases. If this behavior is common, introduce an "Information Discovery Principle" (or equivalent guidance) in DAPM v0.2 to clarify that the methodology organizes and validates information rather than restricting when it may be discovered.

**Status:**
🟡 Pending validation.

---

## Observation 005

**Project:**
Warehouse Operations & Inventory Analytics

**Proposed Improvement:**
Re-evaluate the role of `PROJECT_CASE_JOURNAL.md` for medium and large-scale analytics projects. Consider whether detailed consultant–client discussions should reside within their respective phase documents, allowing the Project Case Journal to be simplified or retired if it no longer provides unique value.

**Evidence:**
During the validation project, a single `PROJECT_CASE_JOURNAL.md` was sufficient because the project was intentionally scoped as a prototype with concise discussions. However, it became evident that in real-world engagements spanning multiple months, the journal could grow into a very large document, making it difficult to navigate and maintain. At the same time, creating detailed phase documents while retaining a comprehensive journal may introduce unnecessary duplication, particularly since the project README already serves as the primary navigation entry point.

**Action:**
Continue using the current Project Case Journal during additional validation projects. Observe whether it consistently provides value beyond the dedicated phase documentation. If future evidence shows that phase documents adequately capture consultant discussions and project history, consider simplifying or retiring the Project Case Journal in a future DAPM release.

**Status:**
🟡 Pending validation.

---

## Observation 006

**Project:**
Warehouse Operations & Inventory Analytics

**Proposed Improvement:**
Evaluate introducing a lightweight **Business-to-Data Mapping** activity immediately after **Data Discovery**. This activity would map each business requirement to the required data sources, tables, and columns before any SQL queries, data cleaning, or Python implementation begins.

**Purpose**

Before implementation, identify:

- Which business requirement is being addressed?
- Which data source contains the required information?
- Which tables are required?
- Which columns are required?
- Which data is not required for the current business objective?

**Benefits**

```
Business Requirement
        │
        ▼
Identify Required Data
        │
        ▼
Select Tables
        │
        ▼
Select Columns
        │
        ▼
SQL Extraction
        │
        ▼
Data Cleaning
        │
        ▼
EDA & Analysis
```

This approach may provide:

- Better alignment between business requirements and implementation.
- Reduced data loading.
- Reduced cleaning effort.
- Simpler SQL queries.
- More maintainable Python code.
- Improved traceability from business question to analytical result.

**Evidence:**
Observed during the transition from Business Requirements to Data Discovery.

**Action:**
Validate across at least five DAPM projects before considering inclusion in DAPM v0.2.0.

**Status:**
🟡 Pending validation.

---

## Observation 007

**Project:**
Warehouse Operations & Inventory Analytics

**Proposed Improvement:**
Introduce **Project Templates** in DAPM to support different types of analytics projects. The core DAPM methodology remains the same, while supporting documentation varies based on the project category.

**Purpose**

Provide predefined template sets for different project types, such as:

- Consultant Projects
- Portfolio Projects
- Internal Business Projects
- Competition Projects

Each project type uses only the documents relevant to its workflow while following the same DAPM phases.

**Benefit**

```
DAPM Methodology
        │
        ▼
Choose Project Template
        │
        ├── Consultant
        ├── Portfolio
        ├── Internal
        └── Competition
                │
                ▼
Use Appropriate Documentation
```

This approach may provide:

- A flexible methodology for different project types.
- Elimination of unnecessary documentation.
- More realistic project workflows.
- Better adoption of DAPM across consulting, portfolio, and competition projects.
- Consistent methodology with customizable documentation.

**Evidence:**
Observed during the Warehouse Operations & Inventory Analytics project while evaluating the suitability of `PROJECT_CASE_JOURNAL.md` for different project categories.

**Action:**
Validate across at least five DAPM projects before considering inclusion in DAPM v0.2.0.

**Status:**
🟡 Pending validation.

---

## Observation 008

**Project:**
Warehouse Operations & Inventory Analytics

**Proposed Improvement:**
Standardize the repository structure by separating **client-provided source data** from **analyst-created artifacts**. Source datasets should be stored independently and remain technology-agnostic.

**Purpose**

Maintain a clear distinction between:

- Client-provided datasets (SQL dumps, CSV exports, Excel reports).
- Analyst-created SQL scripts, Python code, spreadsheets, and dashboards.

**Recommended Structure**

```text
data/
├── raw/
│   ├── database/
│   ├── csv/
│   └── excel/
│
└── processed/

sql/
spreadsheet/
python/
powerbi/
```

**Benefits**

- Clearly separates source data from analytical work.
- Enables multiple tools to use the same dataset.
- Prevents duplication of datasets across technology folders.
- Improves repository organization and maintainability.
- Better reflects how enterprise analytics projects are structured.

**Evidence:**
Observed during the Data Discovery phase while designing the project repository structure.

**Action:**
Validate across at least five DAPM projects before considering inclusion in DAPM v0.2.0.

**Status:**
🟡 Pending validation.

---

## Observation 009

**Project:**
Warehouse Operations & Inventory Analytics

**Proposed Improvement:**

DAPM should remain **tool-agnostic**. During technical phases such as Data Validation, Data Preparation, and Exploratory Data Analysis, the methodology should encourage demonstrating the same analytical task using multiple industry-standard tools where appropriate.

For portfolio projects, the recommended implementation order is:

- Spreadsheet (LibreOffice Calc / Microsoft Excel)
- SQL
- Python (Pandas)

This approach demonstrates that the analyst can perform the same business task using different technologies rather than relying on a single tool.

**Benefit:**

- Demonstrates proficiency in Spreadsheet, SQL, and Python within a single project.
- Allows recruiters to evaluate practical skills across multiple technologies.
- Reinforces that business analysis is independent of the implementation tool.
- Improves the educational value of portfolio projects.
- Makes DAPM suitable for learners with different technical backgrounds.

**Evidence:**

Observed during the implementation planning of the Data Validation phase, where relying solely on Python would not adequately showcase spreadsheet and SQL competencies.

**Action:**

Re-evaluate after Project 5.

**Status:**

🟡 Pending validation.

---

## Observation 010

**Project:**
Warehouse Operations & Inventory Analytics

**Proposed Improvement:**

For technical phases (such as Data Validation, Data Preparation, Exploratory Data Analysis, etc.), adopt a layered documentation structure.

Each phase should contain:

- A primary `README.md` acting as an executive summary.
- Separate implementation folders for each technology (Spreadsheet, SQL, Python, etc.).
- Each technology folder should contain its own implementation files, screenshots, and a dedicated `README.md` documenting the complete workflow.

This separates methodology from implementation while keeping the repository well organized.

**Benefit:**

- Keeps phase documentation concise and easy to read.
- Allows each technology implementation to be self-contained.
- Prevents large, difficult-to-maintain documentation files.
- Improves repository organization.
- Enables recruiters to quickly evaluate skills in a specific technology.

**Evidence:**

Observed during the design of the Data Validation phase, where combining Spreadsheet, SQL, and Python documentation into a single document reduced readability and made navigation difficult.

**Action:**

Re-evaluate after Project 5.

**Status:**

🟡 Pending validation.

---

## Observation 011

**Project:**
Warehouse Operations & Inventory Analytics

**Proposed Improvement:**

Standardize navigation across all technical documentation.

Every phase `README.md` and every technology-specific `README.md` should include a consistent **Navigation** section linking to:

- The parent phase document.
- Other technology implementations within the same phase.
- Previous and next DAPM phases where applicable.

This creates a predictable documentation hierarchy throughout every DAPM project.

**Benefit:**

- Improves document discoverability.
- Makes repository navigation intuitive.
- Reduces the effort required to locate related documents.
- Creates a consistent reading experience across all DAPM projects.
- Improves the overall professionalism of the project documentation.

**Evidence:**

Observed while designing the documentation structure for the Data Validation phase, where cross-linking implementation documents significantly improved accessibility and user experience.

**Action:**

Re-evaluate after Project 5.

**Status:**

🟡 Pending validation.
