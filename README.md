# Natural Disasters Analysis (1900–2024)
Natural disasters (1900–2024): trends in deaths & events, with population normalisation
<hr>
html link - https://maria-kolouchova.github.io/natural-disasters-analysis
<br>
<br>
Exploratory data analysis of global natural disasters using Our World in Data / EM-DAT:
- Which disaster types caused the most deaths?
- How did deaths and event frequency change over time?
- How does the impact look when normalised by the world population?

## Key Findings
- Large historical toll from **droughts** and **floods**, with a clear **break around ~1960**.
- Since ~1960: **sharp rise in event frequency**, especially **extreme weather** and **floods**.
- Relative to global population, **average % deaths per year declined** over time (population growth + preparedness).
- Some hazards (e.g., **wildfires**, **wet mass movements**) show **rising frequency** but irregular fatality spikes.

## Repository Contents
- `notebook.ipynb` – main analysis (EDA, plots, summary table)
- `notebook.html` – rendered HTML version for easy viewing

## Data Source
Our World in Data – Natural Disasters (EM-DAT, CRED / UCLouvain, 2024)  
<https://ourworldindata.org/natural-disasters>

## Methods (brief)
- Cleaning: NA→0 where “no recorded deaths”; death columns cast to int
- Combined categories for clarity: **Extreme Weather & Temperature** (storms, cyclones, heat/cold waves)
- Yearly aggregation for deaths and binary event counts (frequency)
- Population normalisation via interpolated world population (1900–2024)
- Visuals: bar (totals), line (deaths over time), scatter (events per year), decade bar (% population)

## How to View
- Open `notebook.html` directly in your browser, or
- Use nbviewer for the notebook: paste the GitHub `ipynb` link at https://nbviewer.org

## Citation
Data sources: EM-DAT, CRED / UCLouvain (2024) – with major processing by Our World in Data. “Annual number of deaths from droughts – EM-DAT” [dataset]. EM-DAT, CRED / UCLouvain, “Natural disasters” [original data].

## Contact
Maria Kolouchova — feel free to reach out on LinkedIn.
