# Natural Disasters Analysis (1900–2025)

Natural disasters (1900–2025): trends in deaths & fatal events with population normalisation

<hr> View live report: https://maria-kolouchova.github.io/natural-disasters-analysis
<br> 
<br> 
  Exploratory data analysis of global natural disasters using Our World in Data / EM-DAT: - Which disaster types caused the most deaths? - How did deaths and fatal event frequency change over time? - How does the impact look when normalised by the world population?

Note: In this analysis, “event frequency” counts only events with at least one reported death, not all disaster occurrences. Most disasters historically caused no fatalities.

**Key Findings**
* Large historical toll from droughts and floods, with a clear break around ~1960.
* Since ~1960: sharp rise in fatal event frequency, especially extreme weather and floods.
* Relative to the global population, the average % deaths per year declined over time (population growth + preparedness).
* Some hazards (e.g., wildfires, wet mass movements) show rising frequency of fatal events, with irregular spikes in the early 20th century and more consistent fatalities in recent decades.


**Repository Contents**
* analysis.ipynb – full analysis with code
* report.html – full report
* report.pdf – full report

**Data sources:** EM-DAT, CRED / UCLouvain – processed by Our World in Data. “Number of deaths from disasters” [dataset]. EM-DAT, CRED / UCLouvain [original data].
https://ourworldindata.org/natural-disasters

**Methods (brief)**
Cleaning: NA→0 where “no recorded deaths”; death columns cast to int
Combined categories for clarity: Extreme Weather (storms, cyclones, heat/cold waves)
Yearly aggregation for deaths and binary counts of fatal events (events with ≥1 death)
Population normalisation via interpolated world population (1900–2025)
Visuals: bar (totals), line (deaths over time), scatter (fatal events per year), decade bar (% population)

**Data sources:** EM-DAT, CRED / UCLouvain – processed by Our World in Data. “Number of deaths from disasters” [dataset]. EM-DAT, CRED / UCLouvain [original data].

**Contact**

Maria Kolouchova — feel free to reach out on LinkedIn.
