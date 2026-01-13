# Manufacturing Process Bottleneck & QA Impact Analysis

## Overview
This project analyzes manufacturing process efficiency with a specific focus on **QA review as a potential bottleneck**. Using simulated but realistic batch-level and step-level data, the dashboard evaluates cycle time, rework impact, and process variability to identify quality-driven delays in batch release timelines.

The goal of this project is to demonstrate **quality analytics, operational insight, and data storytelling skills** relevant to QA, Operations, and Process Improvement roles in regulated industries.

---

## Objectives
- Identify process steps contributing most to total cycle time
- Evaluate the impact of QA review and rework on batch release timelines
- Analyze variability across batches to detect hidden bottlenecks
- Translate operational data into actionable quality insights

---

## Data Structure
The project uses two Excel sheets:

### Batch Process Data (Step-Level)
- Batch ID
- Process Step (e.g., Weighing, Production, QA Review)
- Step Start & End Time
- Step Duration (hours)
- Rework Flag (Yes/No)

### Batch Summary Data (Batch-Level)
- Batch ID
- Total Cycle Time (hours)
- QA Time (hours)
- QA % of Total Cycle Time
- Rework Indicator

Relationships were established in Power BI using **Batch ID** as the key.

---

## Power BI Dashboard Components

### KPI Cards
- Total Batches Processed
- Average Cycle Time per Batch
- QA % of Total Cycle Time
- Rework-Affected Batches

### Visualizations
- Average Time per Process Step (Bar Chart)
- QA vs Non-QA Time Distribution (Donut Chart)
- Cycle Time by Batch (Column Chart)
- Rework Impact on Cycle Time (Comparative Visual)

---

## Key Insights
- Production steps consume the most time, but QA review introduces greater variability.
- Rework-driven batches significantly extend total cycle time.
- Shorter process steps can still act as bottlenecks due to downstream dependencies.

---

## Tools & Skills Used
- Microsoft Excel (data simulation, cleaning, structuring)
- Power BI (data modeling, DAX measures, dashboard design)
- Quality Metrics & Process Analytics
- Data Visualization & Storytelling

---


## Author
**Aanya Ahluwalia**

