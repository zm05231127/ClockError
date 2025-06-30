# ClockError
Clock Error Database for Seismic Stations in the Ordos Block (2019-2023)

Description: 
This work establishes a five-year clock error database for seismic stations in the Ordos region, providing essential data support for earthquake location, focal mechanism analysis, and seismic velocity change monitoring. This repository contains supplementary data for the study: “High-precision detection of clock errors in seismograms from the Ordos Block using multicomponent noise cross-correlations” (Zhou et al., 2025, under review). 
The dataset comprises:
1. Daily Clock Error Corrections
Location: /clock_error_correction_value/(188 text files, named by station code)
File structure (5 columns):
Column 1: Date (YYYY_JULDAY)
Column 2: Clock error correction (seconds; defined as\Delta t_{\text{corr}} = -\Delta t_{\text{error}})
Column 3: Weighted standard deviation (seconds)
Column 4: Number of component combinations utilized
Column 5: Intermediate values (for reference only)
2. Annual Statistical Visualizations
Location: /clock_error_statistics_figures/years/png

Contact: For technical inquiries, please contact zhoucong323@126.com.
