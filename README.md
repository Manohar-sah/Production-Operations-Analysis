# Production-Operations-Analysis
Production operations analysis using OEE, downtime, WIP, VSM and Power BI to identify performance losses and improvement opportunities.
## Project Overview
This project presents an end-to-end production operations analysis of a multi-stage manufacturing process. The objective was to evaluate production performance, identify major sources of downtime and performance loss, analyze work-in-process (WIP), and identify potential improvement opportunities.
The analysis covers eight production processes:
Mixing,Coating,Drying,Calendering,Slitting,Cell Assembly,Formation,Final Inspection
The project combines production KPI analysis, OEE, downtime analysis, process-level analysis, WIP analysis, Value Stream Mapping (VSM), and an interactive Power BI dashboard.
## Objectives

- Evaluate production performance using OEE
- Analyze Availability, Performance and Quality
- Identify major downtime categories and reasons
- Compare machine and process performance
- Analyze WIP levels and trends
- Develop a Current-State Value Stream Map
- Identify processes requiring further investigation
- Develop improvement opportunities based on the analysis
- Present the results through an interactive Power BI dashboard
## Methodology

The project was performed in the following stages:

### 1. Data Preparation
Production, downtime and WIP data were prepared and validated.

### 2. Production KPI Analysis
Production performance was evaluated using production achievement,
production loss and other relevant production KPIs.

### 3. Machine-Level Analysis
Availability, Performance, Quality and OEE were calculated for
individual machines.

### 4. Process-Level Analysis
Machine-level results were aggregated to process level to compare
the performance of the production processes.

### 5. Downtime Analysis
Downtime was analyzed by category and recorded downtime reason
to identify the major sources of production losses.

### 6. WIP Analysis
Average, maximum and minimum WIP were analyzed together with
the WIP trend over time.

### 7. Current-State VSM
The current production flow was mapped using the process,
WIP, performance and downtime information.

### 8. Power BI Dashboard
The analyzed results were visualized using an interactive
Power BI dashboard.
## Data Preparation
Raw production quality and downtime datasets were inspected for missing values, duplicate records, inconsistent fields and invalid values. The data was subsequently cleaned and prepared for KPI and downtime analysis.
### Raw Data

The original datasets are retained in the `data/raw` folder for transparency.

### Cleaned Data

The cleaned datasets used for subsequent analysis are available in `data/cleaned`.

## Data Quality Analysis

The raw datasets were evaluated before performing KPI calculations.

The analysis included:

- Missing-value checks
- Duplicate checks
- Invalid-value checks
- Data consistency checks
- Range validation
- KPI validation

The detailed findings are available in:

## Production KPI
Production KPIs were calculated to establish the baseline production performance.

## Downtime Analysis
Downtime was analyzed by machine, process, category and recorded downtime reason to identify the major sources of production loss.

## WIP Analysis
WIP was analyzed using average, maximum and minimum WIP and time-based trends to identify potential flow constraints.

## Current-State Value Stream Map

The Current-State VSM integrates the production flow, WIP and process
performance information to provide a system-level view of the current
production state.

## Power BI Dashboard

The Power BI dashboard summarizes the analytical results and provides
an interactive management view of OEE, Availability, Performance,
Quality, downtime and WIP.

## Improvement Opportunities

Based on the analysis, the following areas were identified for further
investigation:

| Process | Issue | Improvement Direction |
|---|---|---|
| Cell Assembly | Electrical downtime | Equipment reliability / maintenance analysis |
| Mixing | Low Performance | Material availability and process analysis |
| Slitting | Low Performance | Setup/changeover analysis |
| Drying | WIP + Performance | Process/alignment investigation |
| Formation | Quality holds | Quality-loss investigation |

