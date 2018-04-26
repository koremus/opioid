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

### substance_by_county.csv

Description: Combined all csv files into data frame. Each column is one county by year, and the file includes a column for county FIPS, state FIPS, mean, lower and upper death rate, cause, region and NAO index 

Source: Combination of all files above

