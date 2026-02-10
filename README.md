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
1.  How has the distribution of genres evolved over the last decade in terms of production volume, and which genres are showing signs of "Content Rot" (High volume but declining IMDb scores)?
2.  Who are the top 10 most frequent actors in the catalog, and does their presence guarantee higher audience ratings and engagement?
3.  What is the relationship between content length (Runtime) and user satisfaction? Is there an "ideal duration" that maximizes scores for Movies vs. Shows?
4.  Is there a strong correlation between marketing success (Popularity) and user satisfaction (Score), or is the platform relying on "overhyped" low-quality content?
5.  Which international production hubs are delivering the highest "Quality-per-Title" ratio, and where are the geographical gaps for content expansion?

---

## 📂 Repository Contents
* **[Amazon_Prime_Strategic_Report.pdf](./report.pdf):** Full project documentation (Business Scope, KPIs, and Architecture).
* **/data:** Source datasets (Titles & Credits).

## 🚀 Roadmap
- [x] Business Scope & KPI Definition.
- [x] Analytical Questions Mapping.
- [ ] **Next Step:** Data Profiling & Power BI Model Development.
