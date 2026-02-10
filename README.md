# 🎬 Amazon Prime Video: Global Catalog Strategic Analytics
**End-to-End Analytics Solution | Power BI & Data Engineering**

## 📌 Project Overview
This project transforms Amazon Prime Video's global metadata into a strategic decision-making tool. Using **Power BI** for visual intelligence and a **Data Lakehouse** approach for data reliability, the goal is to evaluate "Content Health" by balancing IMDb quality with catalog volume.

---

## 🏗️ Technical Architecture (Lakehouse)
To feed the Power BI Semantic Model with high-quality data, I designed a **Medallion Architecture**:

* **Bronze:** Raw ingestion of titles and credits.
* **Silver:** Data cleaning and resolving homonyms (addressing the person_id vs. name delta).
* **Gold (Power BI Ready):** Curated tables optimized for dashboard performance.

---

## 💡 Business Intelligence & KPIs
I have defined the strategic pillars and **5 Core Analytical Questions** that the Power BI dashboard will address:

### 🎯 Key Performance Indicators (KPIs)
* **Content Health Index:** Distribution of quality vs. volume.
* **Global Production Reach:** Mapping production hubs worldwide.
* **Talent Impact Factor:** Measuring the weight of directors/actors on catalog value.

### 🔍 Analytical Questions
1.  What is the ratio between Movies and TV Shows across production hubs?
2.  How does critical acclaim correlate with production volume per country?
3.  Which decades represent the highest value in the current catalog?
4.  How do specific talents influence the "Quality Score" of their genres?
5.  What are the runtime patterns for top-rated vs. low-rated content?

---

## 📂 Repository Contents
* **[Amazon_Prime_Strategic_Report.pdf](./report.pdf):** Full project documentation (Business Scope, KPIs, and Architecture).
* **/data:** Source datasets (Titles & Credits).

## 🚀 Roadmap
- [x] Business Scope & KPI Definition.
- [x] Analytical Questions Mapping.
- [ ] **Next Step:** Data Profiling & Power BI Model Development.
