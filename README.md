# PermitPulse 2.0

Development × Traffic Intelligence for the City of Sugar Land

Live Application:
[https://permitpulse-20-mdhhst74mfb4qkqghxsg3i.streamlit.app/](https://permitpulse-20-mdhhst74mfb4qkqghxsg3i.streamlit.app/)


## Executive Summary:

PermitPulse 2.0 is an interactive dashboard that helps the City of Sugar Land analyze the relationship between development activity and traffic conditions. It integrates building permit records with traffic information and traffic event data to provide actionable insights for planning and infrastructure decision-making.


## Problem Statement:

Development permitting and traffic systems are often managed separately, making it difficult to:

- Identify areas experiencing both high development and traffic activity  
- Anticipate infrastructure strain  
- Monitor permitting efficiency  
- Provide data-driven insights for planning discussions

PermitPulse 2.0 addresses this gap by integrating these datasets into a single analytical platform.


## Solution Overview:

The platform integrates three datasets:

- Building Permits:** applications, issuance dates, valuations, ZIP codes  
- Traffic Information:** timestamped traffic records  
- Traffic Events:** disruptions with defined start and end times  

It performs:

- Data cleaning and standardization  
- Date parsing and duration calculations  
- ZIP-level aggregation and scoring  
- Detection of unusually slow permit issuance  
- Interactive visualizations for exploration


## Key Capabilities:

Development Trend Monitoring
- Monthly permit volume visualizations  
- ZIP code and application date filters  
- Valuation aggregation  

Traffic Event Analysis
- Daily traffic event counts  
- Comparison of traffic patterns with development trends  

Urban Stress Score (ZIP-Level)
- Combines Development Pressure Index (DPI) and Traffic Stress Index (TSI)
- Highlights ZIP codes where development intensity and traffic events overlap  
- Supports infrastructure prioritization and planning review

Permit Delay Detection
- Flags permits that took unusually long to issue  
- Supports internal process evaluation and benchmarking  

Data Export
- Filtered permit datasets can be downloaded as CSV for further analysis


## How to Use This Dashboard

1. Open the live application link above.  
2. Use the left sidebar filters to select ZIP codes and application date range.  
3. Review the "Permit Volume Over Time" chart to identify development trends.  
4. Compare with the "Traffic Events Over Time" chart to see traffic impact patterns.  
5. Examine the "Urban Stress Score" table to identify ZIP codes with overlapping development and traffic activity.  
6. Use the "Delay Watch" section to see unusually slow permits.  
7. Export filtered permit data if needed.
