# Projects

My projects focus on translating real oncology research workflows into
structured, high-quality data that can be reliably analyzed and reused.
Across these efforts, I emphasize clinical context, variable definition,
data quality, and transparency of assumptions.

## 1. Correlative Sample LIMS (PostgreSQL)

This system was designed around real oncology trial workflows, including
treatment cycles, progression events, biomarker-driven sampling, and
patient-level metadata that materially affects downstream analysis.

**Problem**  
Clinical trial biospecimen data is often fragmented across spreadsheets,
EDCs, and ad hoc tracking systems, making it difficult to understand
sample provenance, treatment context, and downstream analytic readiness.

**Approach**
I designed a normalized PostgreSQL schema to manage correlative clinical
trial samples across their full lifecycle, from collection through
storage, movement, and analysis. The design reflects real oncology trial
workflows, including treatment cycles, clinically annotated sampling,
and operational constraints.

**What I Built**
- Normalized relational PostgreSQL schema for studies, subjects, visits, samples, aliquots, storage units, and movement events
- Controlled vocabularies and lookup tables to enforce consistency
- Explicit handling of treatment context and clinically meaningful timepoints
- Sample lifecycle tracking (collection → storage → movement)
- CDISC/CLIA-aware design considerations

**Data & Clinical Reasoning Demonstrated**
- Translating treatment cycles and clinical milestones into structured variables
- Preserving sample provenance and temporal context
- Designing schemas that support downstream QC and analysis, not just tracking

**Key Skills**
- Relational data modeling
- Schema-first thinking
- Vairable definition
- Metadata standards
- Clinical workflow translation
- Documentation and version control

🔗 Repo: https://github.com/bonnielacroix/correlative_samples_database

---

## 2. Oncology Data Reasoning & QC Frameworks

This project reflects how clinical reality—pathology findings, treatment
timing, and patient characteristics—must be translated into precise,
auditable variables for real-world data analysis.

**Problem**
Clinical and real-world oncology data often contains ambiguity: conflicting
dates, unclear treatment intent, evolving disease status, and inconsistent
variable definitions across sources.

**Approach**
This project documents how I reason about oncology clinical information
when defining variables for analysis. Rather than focusing on tools, it
focuses on decision logic, source prioritization, and documentation of
uncertainty.

**What I Document**
- Treatment date reconciliation across structured records and clinical notes
- Variable Definitions for treatment start, restart, progression, and end
- Source prioritization (structured vs notes)
- Handling missing, conflicting, or ambiguous clinical information
- Appropriate use and limitations of patient-level metadata

**Data & Clinical Reasoning Emphasized**
- Understanding what clinical variables represent biologically and temporally
- Making assumptions explicit and auditable
- Designing variables with downstream analytic impact in mind

**Key Skills Demonstrated**
- Clinical reasoning
- Data quality
- Variable Definition
- Real-World Data Interpretation and QC
- Documentation Clarity
- Decision Traceability

🔗 Repo: https://github.com/bonnielacroix/oncology-data-reasoning

---

## 2. Equipment Usage Tracking & Analytics

**Goal:**  
Automate equipment usage logging and generate operational insights.

**What I Built**
- PowerShell scripts capturing run metadata
- User and instrument normalization
- SharePoint-based ingestion
- Power BI dashboards with cumulative metrics

**Key Skills Demonstrated**
- Automation
- ETL-style thinking
- Operational analytics
- Data quality controls

🔗 Repo: https://github.com/bonnielacroix/equipment-usage-tracking

---
