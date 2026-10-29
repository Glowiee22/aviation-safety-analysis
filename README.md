# Aviation Safety Analysis

## Project Overview
This project analyzes aviation accident data to identify patterns related to aircraft safety. The goal is to help the client understand differences in fatal and serious injuries and aircraft destruction across aircraft makes, airplane types, weather conditions, and engine types.

## Business Problem
The client wants to understand which aircraft makes and models show lower fatal/serious injury fractions and aircraft destruction rates in the available accident records. These findings can support further investigation into aircraft safety.

## Data Cleaning
The dataset was cleaned using Python and Pandas. The analysis focused on airplane accidents from 1983 onward, excluded amateur-built aircraft, removed records without required make/model information, and retained makes with at least 50 records. Injury information was used to calculate the fatal/serious injury fraction, and aircraft damage information was used to calculate the destruction rate.

## Analysis
The analysis examined:
- Safety measures by aircraft make and aircraft size.
- Fatal/serious injury fractions for specific airplane types.
- Injury and aircraft destruction rates by weather condition.
- Injury and aircraft destruction rates by engine type.

Tables, summary statistics, and visualizations were used to compare the results.

## Key Findings
The analysis found differences in injury fractions and aircraft destruction rates across aircraft makes, airplane types, weather conditions, and engine types. In the accident records, accidents in instrument meteorological conditions had higher mean injury and destruction rates than those in visual meteorological conditions. Engine types also showed different rates, although the number of records varied substantially between categories.

## Limitations
This analysis uses accident records rather than all flights. The results therefore do not measure the probability of an accident or injury per flight, and they do not prove that a particular aircraft or condition causes safer outcomes. Some categories have small sample sizes, so their results should be interpreted cautiously.

## Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- GitHub
