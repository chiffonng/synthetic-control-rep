# Synthetic Control

This is a response to the 2021 study "[Philadelphia’s Excise Tax on Sugar-Sweetened and Artificially Sweetened Beverages and Supplemental Nutrition Assistance Program Benefit Redemption](https://pmc.ncbi.nlm.nih.gov/articles/PMC8630475/)" by Benjamin W. Chrisinger. It was done in R as the final assignment for Minerva University class on Causal Inference taught by Professor Alexis Diamond (one of the people who created synthetic control method and package).

Motivated by unexpected effects on lower-income shoppers' behavior and increased SNAP benefit redemption in neighboring counties, we aimed to replicate the synthetic control method and conduct a robustness check. Our analysis seeks to understand two causal results from the paper: 1) whether the excise tax on sugar and artificially sweetened beverages could indeed reduce the consumption of them among the low-income consumers in Philadelphia County; 2) whether this excise tax led to increased SNAP benefit redemption in the neighbor counties, potentially meaning that low-income individuals in Philadelphia County traveled to shop. 

While we are able to replicate similar trends, the magnitude of the effects differs, and our models lack robustness. We attribute these disparities to our lack of access to final data used (we cleaned the data ourselves) and variations in synthetic control implementations. Until these discrepancies are addressed, we withhold definitive conclusions regarding the impact of the introduced excise tax in Philadelphia County and its neighboring counties.

## Contritbution Statement
Chiffon: dedicated extensive amount of time to clean the data, write the code to replicate the figure and to produce the leave-one-out analysis. Contributed to the write-up by helping to interpret the results and reviewing.

Aida: reviewed the code, contributed to the leave-one-out analysis and debugging. Produced the write-up of the assignment, ensured the following of assignment instructions.
