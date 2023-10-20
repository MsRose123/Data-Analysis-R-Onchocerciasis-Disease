## Data Analysis of Onchocerciasis Disease in Sierra Leone, Africa

##### Data

- Data used : Secondary data on Onchocerciasis (River-blindness) from Sierra Leone, Africa
- Dataset Variables:

- id - Unique number
- mf - Microfilaria Infection: 1 = yes, 0 = no
- area - Area of residdence: 1 = Rainforest, 0 = Savannah
- agegrp - Age Group(years): 0 = 5-9, 1 = 10-19, 2 = 20-39, 3 = 40+
- sex - 0 = male, 1 = female
- lesions - Eye Lesions: 0 = yes, 0 = no

- Null hypothesis: Living in the Rainforest or Savannah area does not affect the risk of having Microfilarial Infection.

##### Methods

- Exploratory Analysis
- Linear Regression

##### Software and Packages used

- R, RStudio
- gtsummary, readxl, tibble, Hmisc, purrr

##### Exploratory Analysis Results

- Population: 1302
- Comparison: rainforest, savnnah
- Confounding: Sex, Age
- Primary Outcome: Microfilaria Infection
- Secondary Outcome: Eye Lesions

##### Conclusions

- The risk of Microfilarial Infection at baseline is 0.689 .
- In Rainforest area, the risk is 0.789, while in Savannah area it is 0.515.
- The area that people are living in has biggest influence on the risk of Microfilarial Infection.
- Age group and sex  affect the risk of infection.
- Elder people are more likely to get infected.
- Male have higher risk of infection.
