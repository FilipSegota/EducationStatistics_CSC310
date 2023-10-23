# EducationStatistics_CSC310
## Info
**Author:**
Filip Segota  
**Class:**
CSC 310 (Advanced CS Topics-Big Data), Spring 2021  
**Assignment:**
Advanced Reporting

## Overview
This program analyzes the given dataset from The World Bank. THE DATASET IS NOT IN THE REPOSITORY BECAUSE IT'S TOO BIG (it's cited in the Resources section). The dataset encompasses data on education expenditure for every country in the world. The program includes the breakdown of countries that are reporting expenditures, grouping them by continent, and a list of all countries that did not report, sorted by continent as well. 

## Program Summary
  - Import libraries, define the format of files to be combined, combine them, read, and show the combined file.
  - Find countries that reported the income, and ones that didn't, and show them
  - Create a function for finding countries and use it to find:
    - Ones that contributed (cleaned up using .dropna)
    - Ones that didn't contribute (cleaned up using .dropna)
    - Combine those two into one table
  - Show only the countries that are using $ as their currency
  - Group countries by continent
    - Group countries that reported
    - Group countries that didn't report
  - Show only certain regions (both for countries that reported and that didn't)
  - Sort the data by region

## Resources
The World Bank|Data Catalog - https://datacatalog.worldbank.org/search/dataset/0038480
