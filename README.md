## Overview
A project on the analysis of housing affordability and financial expenses over a long period.

## Technologies and Tools Used
The project is limited to the use of Excel and its built-in data analysis tools.

## Data Source
The data represents statistics for the years 2005-2013, provided by the "Housing Affordability Data System" [(HADS)](https://archives.huduser.gov/portal/datasets/hads.html), presented by the Department of Housing and Urban Development.
**Data sets are divided at intervals of 2 years (2005, 2007, 2009, 2011, 2013), each set containing 50-60 thousand records.**

The data includes a legal, economic, and physical overview of the state of housing and its residents. Specifically, the data includes information about:
- The number of rooms in a housing unit
- The year of construction of the housing unit
- Legal status of the housing unit (free or occupied, rent or ownership)
- Family structure of the residents
- The number of apartments in the building
- Market value, housing expenses
- Number of residents in a housing unit, household income
- Type of residential area

## Data Cleaning
In total, the statistics have more than 90 variables, so to reduce the complexity of the analysis, **only 27 of the most important variables were retained** to answer the questions posed.
Description of the variables used: [List-of-variables-used.pdf](./List-of-variables-used.pdf)

The importance level of the variables was determined based on the study of the [documentation](https://archives.huduser.gov/portal/datasets/hads/HADS_doc.pdf) for the data source.
In particular, most of the variables related to AMI (Area Median Income), adjustments to income and expenses for inflation, and values demonstrating the relativity of the main metrics to these variables were removed.
They are useful for studying different population categories, which is not the focus of the project.

**Records where the value of the housing unit price was missing or suspicious (negative or too low values) were also removed.**
As the project focuses on the analysis of housing affordability, the reliability of the price is critical.


