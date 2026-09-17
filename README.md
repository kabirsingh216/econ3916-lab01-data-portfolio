# econ3916-lab01-data-portfolio
The Data Portfolio — Big Mac Index Analysis
Objective

This project analyzes The Economist's Big Mac Index across 57 countries and 45 time periods (2000–2026) to evaluate currency valuation using purchasing power parity theory.

Methodology
Sourced raw Big Mac Index data directly from The Economist's public GitHub repository
Computed implied Purchasing Power Parity (PPP) exchange rates for each country-period observation
Calculated over/undervaluation percentages relative to actual market exchange rates
Classified the dataset's structural dimensions, identifying cross-sectional, time-series, and panel components
Conducted a missing data diagnosis, determining that Russia's exclusion from later periods followed a Missing Not At Random (MNAR) pattern tied to its removal from the index following market exit
Built a bar chart visualizing currency valuations across the most recent cross-section (July 2024)
Built a time-series visualization comparing valuation trends for selected currencies across the full sample period
Key Findings
Switzerland consistently ranks among the most overvalued currencies in the dataset, showing a +41.8% valuation premium in the July 2024 cross-section (n=54 countries)
Japan stands out as a persistent outlier on the other end of the spectrum, remaining undervalued on average in every decade covered by the series (2000s, 2010s, 2020s)
These patterns are consistent with long-documented deviations from PPP theory, driven by factors such as labor cost differentials, trade barriers, and monetary policy divergence
