# 🏥 Hospital Emergency Room Analytics Dashboard | Advanced Excel

## 🔍 Business Problem

Hospital emergency rooms face constant pressure to optimize patient flow, minimize wait times, and improve patient satisfaction — all while managing limited resources. Without clear visibility into operational data, hospital management cannot make timely, informed decisions on staffing, department capacity, or service quality.

**The goal:** Build a dynamic, interactive Excel dashboard that gives hospital leadership real-time visibility into ER operations — covering patient flow, demographics, department referrals, wait times, and satisfaction scores — to enable data-driven decisions that improve efficiency and patient experience.

### Key Business Questions Answered
- What are the monthly, daily, and hourly trends in patient visits and wait times?
- Where are the bottlenecks causing service delays?
- Who are the patients (age, gender) and how do demographics relate to visit patterns?
- Which departments receive the most ER referrals and what is the gender distribution?
- Which ER services require immediate attention based on patient satisfaction?

---

## 🛠️ How It Was Solved

A full data pipeline was built entirely within Excel across 4 stages:

### Stage 1 — Import & Ingest (Power Query)
Raw operational ER data was imported and cleaned using Power Query — handling missing values, standardizing formats, and structuring data for analysis.

### Stage 2 — Data Modelling (Power Pivot)
Relationships were established between multiple tables in Power Pivot to create a robust data model, enabling complex cross-table calculations.

### Stage 3 — DAX Measures
Custom DAX measures were written to calculate key performance indicators including:
- Average patient wait time
- % of services experiencing delays
- Patient satisfaction scores by department and age group
- Referral volume by department and gender

### Stage 4 — Dynamic Dashboard (Pivot Tables & Pivot Charts)
An interactive dashboard was built using Pivot Tables and Pivot Charts with slicers for year and month filtering, enabling management to drill into any time period for targeted analysis.

---

## 📊 Output & Key Insights

The dashboard delivered actionable insights that directly informed hospital operations:

- ⏰ **Staffing optimization** — hourly and daily patient flow patterns identified peak demand periods, enabling dynamic staffing schedules aligned to patient volume
- 😟 **Satisfaction gaps** — low satisfaction scores in Cardiology and Gastroenterology referral pathways and in age brackets 40–49 and 70+ flagged areas needing immediate process review
- 🏨 **Top referral departments** — General and Orthopedics identified as primary referral destinations, pointing to where process improvements would have the greatest impact
- ⚠️ **Delay crisis** — with **62% of services experiencing delays**, the dashboard recommended a hospital-wide initiative to identify and eliminate operational bottlenecks
- 📅 **Dynamic filtering** — management can visualize operations for any specific year or month, enabling targeted and timely decision-making

---

## 🛠️ Tools & Skills Used

**Excel:** Power Query · Power Pivot · DAX · Pivot Tables · Pivot Charts · Slicers

**Skills Demonstrated:**
- End-to-end data pipeline in Excel (ingest → clean → model → visualize)
- DAX measure writing for healthcare KPIs
- Dynamic dashboard design for non-technical executive audiences
- Operational analytics and patient flow analysis
