# 🎬 Amazon Prime Video: Global Catalog Strategic Analytics
**End-to-End Data Engineering Project | Medallion Architecture Design**

## 📌 Project Overview
This project focuses on building a strategic data solution for Amazon Prime Video's global catalog. By integrating title metadata and talent credits, the goal is to transform raw streaming data into a "North Star" for content decision-makers, moving from intuitive selections to evidence-based investments.

> **Note:** While this README is in English, the full project documentation is written in **Portuguese**.

---

## 🏗️ Data Lakehouse Architecture
The technical foundation follows the **Medallion Architecture**, ensuring data reliability and a clear lineage from raw ingestion to business insights:

1.  **Bronze Layer (Raw):** Preservation of original titles and credits datasets.
2.  **Silver Layer (Cleansed):** Data quality enforcement, handling missing values, and resolving homonyms (as identified in the initial data audit).
3.  **Gold Layer (Curated):** Business-level aggregates optimized for the Power BI Semantic Model.

---

## 💡 Strategic Planning (Phase 1 Complete)
I have successfully defined the business framework, focusing on five core analytical pillars:

### 1. Analytical Questions (The 5 Core Pillars)
The project is designed to answer five fundamental business questions:
* **Market Composition:** What is the ratio between Movies and TV Shows across different production hubs?
* **Critical Success vs. Volume:** How does critical acclaim (IMDb scores) correlate with production volume by country?
* **Historical Trends:** Which years or decades represent the highest value in the current catalog?
* **Talent Connectivity:** How do specific directors and actors influence the overall "Quality Score" of a genre?
* **Content Duration Patterns:** Are there significant runtime differences between top-rated and low-rated content?

### 2. Key Performance Indicators (KPIs)
Based on the analytical questions, the following KPIs were established:
* **Content Health Index:** Distribution of quality scores across the catalog.
* **Global Diversity Ratio:** Tracking the geographic origin of content.
* **Talent Impact Factor:** Measuring the weight of specific cast/crew on catalog prestige.
* **Release Velocity:** Monitoring the pace of content additions over time.

---

## 📂 Repository Contents
* **[Amazon_Prime_Strategic_Report.pdf](./EDSTD_template.pdf):** Full technical report covering Business Scope, the 5 Analytical Questions, and KPI Definitions.
* **/data:** Source datasets (Titles & Credits).

## 🚀 Current Roadmap
- [x] Business Context & Strategic Scope definition.
- [x] Definition of the **5 Core Analytical Questions**.
- [x] **KPI Mapping** and Metric calculation logic.
- [x] Data Lakehouse Architecture design.
- [ ] **Next Step:** Detailed Data Profiling & Quality Audit.
- [ ] Implementation of ETL Pipelines (Bronze to Silver).
