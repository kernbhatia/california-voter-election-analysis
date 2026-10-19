# California Voter & Election Analysis, 2020–2024

## Overview

This project examines changes in voter turnout, presidential vote share, and county-level demographic characteristics across eight California counties between 2020 and 2024.

The analysis focuses on:

- Los Angeles County
- Orange County
- Riverside County
- San Diego County
- Sacramento County
- Merced County
- Fresno County
- Shasta County

These counties were purposively selected to represent variation in population size, geography, urbanization, and regional political context across California.

## Research Question

**How did voter turnout and presidential voting patterns change across selected California counties between 2020 and 2024, and how were those changes associated with county-level demographic and socioeconomic trends?**

## Key Areas of Analysis

The project examines three main areas:

### 1. Voter Turnout

General election turnout is compared across:

- 2020
- 2022
- 2024

Turnout is measured as:

**Ballots Cast ÷ Registered Voters**

The 2022 election is treated separately as a midterm election, while 2020 and 2024 are presidential election years.

### 2. Presidential Vote Share

Presidential results from 2020 and 2024 are compared to measure changes in:

- Democratic presidential vote share
- Republican presidential vote share

The analysis focuses on percentage-point change rather than raw vote totals in order to make counties of different population sizes more comparable.

### 3. Demographic and Socioeconomic Change

County demographic characteristics are drawn from the U.S. Census Bureau's American Community Survey 5-Year Estimates.

Variables examined include:

- Population
- Median household income
- Educational attainment
- White population
- Black or African American population
- Asian population
- Hispanic or Latino population

Particular attention is given to demographic and socioeconomic variables that changed most substantially between 2020 and 2024.

## Data Sources

### Election Data

California Secretary of State

Election data includes:

- Registered voters
- Ballots cast
- General election turnout
- Presidential candidate vote totals
- Presidential vote share

### Demographic Data

U.S. Census Bureau  
American Community Survey 5-Year Estimates

Where applicable, income data is compared in inflation-adjusted dollars so that changes over time reflect changes in real purchasing power rather than nominal dollar increases alone.

## Methodology

The analysis combines election and demographic data at the county level.

For each county, the project calculates:

- Change in voter turnout
- Change in Democratic presidential vote share
- Change in Republican presidential vote share
- Change in median household income
- Changes in selected demographic characteristics

The project then compares the magnitude of these changes across counties to identify possible county-level associations.

For example:

- Did counties with larger real-income increases also experience larger changes in Republican vote share?
- Did changes in racial composition coincide with changes in Democratic or Republican vote share?
- Did counties with different socioeconomic profiles experience different turnout patterns?

These relationships are treated as associations rather than causal relationships.

## Important Limitations

This project uses aggregate county-level data.

As a result, the analysis cannot determine:

- How individual voters changed their voting behavior
- Whether members of a particular racial or demographic group changed party preference
- Whether demographic changes directly caused electoral changes

Observed relationships may also be influenced by factors not included in the analysis, including candidate characteristics, campaign activity, national political conditions, local issues, migration, age distribution, and changes in voter participation.

The eight counties examined are also not intended to constitute a statistically representative sample of all California counties.

## Visualizations

The final report includes visualizations comparing:

- Voter turnout across election years
- Democratic and Republican presidential vote-share changes
- Median household income changes
- Demographic composition
- Relationships between demographic change and electoral change

Scatterplots are used where appropriate to examine county-level associations between socioeconomic and electoral variables.

## Project Files

The repository is organized as follows:

```text
├── README.md
├── California_Voter_Election_Analysis.pdf
├── data/
│   └── election_and_demographic_data.xlsx
├── charts/
│   └── project_visualizations
└── sources/
    └── data_sources.md
