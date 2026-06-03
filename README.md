# Infrastructure Programme Performance and Data Quality Monitor

## Project Overview
A four-page Power BI dashboard modelling a capital infrastructure 
programme delivery environment, built to demonstrate programme 
performance monitoring, data quality governance, and executive MI 
reporting capabilities aligned to regulated programme environments.

## Context
AquaTrack NW is a simulated infrastructure programme modelled on 
AMP8-style capital delivery programmes run by regulated UK utilities. 
The programme covers four workstreams across five regions of the 
North West — Mains Replacement, Wastewater Treatment, Network 
Monitoring, and Leakage Reduction.

## Problem Statement
Large infrastructure programmes generate data from multiple sources 
simultaneously. Without a centralised view of performance and data 
quality, leadership risks making decisions on incomplete or inaccurate 
information, regulatory deadlines get missed, and risks go undetected 
until it is too late to act.

## What This Dashboard Solves
- Tracks milestone adherence across four workstreams in real time
- Monitors data quality across five reporting feeds weekly using 
  completeness, accuracy, consistency, and timeliness scoring
- Identifies and ranks risks by severity using RAG status logic
- Delivers plain-language executive MI summaries for senior 
  leadership decision-making

## Dashboard Pages
| Page | Purpose |

| Programme Overview | Milestone adherence, completion rates, RAG status by workstream |
| Data Quality Monitor | Weekly quality scoring across five data sources with trend analysis |
| Risk and Anomaly Tracker | Risk matrix, severity ranking, and open risk register |
| MI Leadership Summary | Executive summary for senior stakeholders with plain-language commentary |

## Tools Used
- Power BI Desktop — dashboard development and DAX measures
- Microsoft Excel — data source files
- DAX — calculated measures and KPI logic
- Data modelling — star schema with central workstream dimension table

## Data Sources
Three Excel files simulating live system feeds:
- Programme_Milestones.xlsx — 80 milestone rows across four workstreams
- Data_Quality_Log.xlsx — 260 weekly quality assessments across five sources
- Risk_Register.xlsx — 25 identified programme risks with scoring and mitigation

## Key Findings from the Data
- Overall programme completion rate at 35 percent
- Data quality across all sources sitting at 75 to 80 percent, 
  below the 90 percent target but on an improving trend
- 8 Red-rated risks identified requiring leadership attention
- Data quality and regulatory delivery risks carry the highest scores

## Note on Optimisation
Dashboard is functional across all four pages. Performance 
optimisation and visual refinements are currently in progress 
including incremental data refresh configuration and enhanced 
conditional formatting across all pages.

## Screenshots
### Page 1 — Programme Overview
Screenshot 2026-06-04 002245.png

### Page 2 — Data Quality Monitor
![Data Quality Monitor](Dashboard_Screenshots/Page2_Data_Quality_Monitor.png)

### Page 3 — Risk and Anomaly Tracker
![Risk Tracker](Dashboard_Screenshots/Page3_Risk_Anomaly_Tracker.png)

### Page 4 — MI Leadership Summary
![MI Summary](Dashboard_Screenshots/Page4_MI_Leadership_Summary.png)

## Author
Kunal Patil — Data Analyst
[LinkedIn](https://linkedin.com/in/kunal3008) | 
[GitHub](https://github.com/kunalpatil3008)
