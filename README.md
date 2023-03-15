# Investigating-SVI-and-Heart-Related-Deaths

## Data Sources
### Heart Related Deaths
### ATSDR Social Vulnerability Indexes

## Visualizations
- Top and bottom 3 states of deaths per 100k population
- Biggest decreases and increases in deaths per 100k, top and bottom.
- How do feature importances change through the years?

## Questions
- What laws or cultural changes could of had an impact?

## Alternative Applications with this Approach
- Investigating relationship between other causes of death and social vulnerability.
    - Example: Trauma deaths, Cancer deaths, etc.

## Category Creation
- The following stats are from the in death for each two year increment from 2014 thru 2020.
    - Mean: 8.1
    - Standard Deviation: 57.8
- Using these stats counties are assigned into a risk category based on their change.
    - 0 - Low: Change < -49.7
    - 1 - Standard: Change between -49.7 and 65.9
    - 2 - High: Change > 65.9

## To-Do
- In visuzlizations.ipynb counties with low population significantly alter deaths per 100k population, investigate binning? - Limitation?

## Resources