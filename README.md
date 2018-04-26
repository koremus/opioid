# opioid
county-year-substance-estimates

## Repo structure

```
opioid:
├───data
|   └───substance_by_county
├───docs
├───raw_data
│   ├───IHME(by alphabet)
|   |   └───IHME(by state)
│   ├───nao-pc
|   └───nao-slp
└───codeR
```
## Data sources

### 

Description: Substance Use Disorders and Intential Injuries Mortality Rates by County by Year 1980-2014
Institute for Health Metrics and Evaluation (IHME)

Source: http://ghdx.healthdata.org/record/united-states-substance-use-disorders-and-intentional-injuries-mortality-rates-county-1980

Description: The winter (December thru March), station-based index of the NAO is based on the difference of normalized sea level pressure (SLP) between Lisbon, Portugal and Stykkisholmur/Reykjavik, Iceland since 1864. Positive values of the NAO index are typically associated with stronger-than-average westerlies over the middle latitudes, more intense weather systems over the North Atlantic and wetter/milder weather over western Europe. Monthly, seasonal and annual indices using slightly different data sources for the southern station are also available.

Source: https://climatedataguide.ucar.edu/climate-data/hurrell-north-atlantic-oscillation-nao-index-station-based

Description: The winter (December thru March), principal-component (PC)-based indices of the North Atlantic Oscillation (NAO) are the time series of the leading Empirical Orthogonal Function (EOF) of SLP anomalies over the Atlantic sector, 20°-80°N, 90°W-40°E. These indices are used to measure the NAO throughout the year, tracking the seasonal movements of the Icelandic low and Azores high. These movements are illustrated in the Figures on this page. Positive values of the NAO index are typically associated with stronger-than-average westerlies over the middle latitudes, more intense weather systems over the North Atlantic and wetter/milder weather over western Europe.

Source: https://climatedataguide.ucar.edu/climate-data/hurrell-north-atlantic-oscillation-nao-index-pc-based

### substance_by_county.csv

Description: Combined all csv files into data frame. Each column is one county by year, and the file includes a column for county FIPS, state FIPS, mean, lower and upper death rate, cause, region and NAO index 

Source: Combination of all files above

