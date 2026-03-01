PermitPulse 2.0
Development x Traffic Intelligence for the City of Sugar Land

Live Application:
https://permitpulse-20-mdhhst74mfb4qkqghxsg3i.streamlit.app/

Executive Summary:
PermitPulse 2.0 is an integrated urban analytics dashboard designed to help the City of Sugar Land better understand how development activity interacts with traffic conditions.
By combining building permit records with traffic data and traffic event logs, the platform provides a unified, data-driven view of development intensity, traffic stress, and permitting efficiency at the ZIP-code level.
The system transforms existing open-data resources into a decision-support tool that promotes proactive planning, operational transparency, and infrastructure prioritization.

Problem Statement:

  Development permitting and traffic systems are often analyzed separately. This separation makes it difficult to:
    -Identify geographic areas experiencing simultaneous development pressure and traffic disruption
    -Anticipate infrastructure strain
    -Monitor permitting efficiency at scale
    -Provide data-backed insights for planning discussions

  PermitPulse 2.0 addresses this gap by integrating these datasets into a single analytical framework.


Solution Overview:

  The platform integrates three structured datasets:
    -Building permit data (applications, issuance dates, valuations, ZIP codes)
    -Traffic information (timestamped traffic data)
    -Traffic events (disruptions with defined time windows)

  The application automatically:
    -Cleans and standardizes data
    -Parses and calculates issuance timelines
    -Aggregates metrics by ZIP code
    -Normalizes and scores development and traffic indicators
    -Detects statistical outliers in permit processing time
    -Presents findings through interactive visualizations


Key Capabilities:

  Development Trend Monitoring:
    -Monthly permit volume visualization
    -Filtering by ZIP code and application date
    -Total valuation aggregation
    -This allows planners to identify growth spikes or sustained expansion periods.


  Traffic Event Analysis:
    -Daily traffic event counts
    -Time-series comparison with development trends
    -This enables identification of potential temporal overlaps between construction activity and traffic disruptions.


  Urban Stress Score (ZIP-Level):

    PermitPulse introduces a composite index to highlight areas experiencing concentrated development and traffic activity.
    The Urban Stress Score combines:
      -Development Pressure Index (DPI): Weighted permit count and total valuation
      -Traffic Stress Index (TSI): Normalized traffic event density

    Higher scores indicate ZIP codes where development intensity and traffic events overlap, signaling potential infrastructure strain.
    This metric supports:
      -Infrastructure prioritization
      -Corridor monitoring
      -Planning review discussions
      -Capital improvement alignment
      

  Permit Delay Detection:

    The “Delay Watch” feature uses a robust statistical method (median absolute deviation) to flag permits that took unusually long to issue relative to similar permit types.
    This supports:
      -Internal workflow evaluation
      -Service-level benchmarking
      -Process transparency
      

How to Use This Dashboard:

  Open the live application link above.
  Use the left sidebar filters to:
    -Select one or more ZIP codes
    -Adjust the permit application date range
  Review the “Permit Volume Over Time” chart:
    -Identify growth surges or sustained development patterns
  Compare with the “Traffic Events Over Time” chart:
    -Observe whether traffic disruptions align with development spikes
  Examine the “Urban Stress Score” table:
    -Higher scores indicate overlapping development and traffic activity
    -Use this to identify ZIP codes that may require infrastructure review
  Review the “Delay Watch” section:
    -Identify permits that experienced unusually long issuance timelines
  Export filtered permit data if further analysis is required.
