# CRA Fourth Basis Revenue Sharing Data (2025-2030)

## Overview
This dataset contains the complete revenue sharing allocation for Kenya's 47 county governments based on the Commission on Revenue Allocation (CRA) Fourth Basis for Financial Years 2025/26 - 2029/30.

## Source Document
**CRA-The-Fourth-Basis-for-revenue-sharing-among-counties-2025-2030.pdf**
Published: December 31, 2024
Commission on Revenue Allocation, Kenya

## File: cra-revenue-share-2025-2030.csv

### Revenue Sharing Formula (Fourth Basis)
The allocation is based on five parameters with the following weights:
- **Population**: 42%
- **Equal Share**: 22%
- **Poverty**: 14%
- **Income Distance**: 13%
- **Geographical Size**: 9%
- **Total**: 100%

### Column Descriptions

#### Basic County Information
- **County**: Name of the county
- **Population_2019**: Total population from 2019 Kenya Population and Housing Census
- **Geographic_Size_Sq_Kms**: Land area in square kilometers

#### Poverty Indicators (Kenya Poverty Report 2022)
- **Poverty_Rate_%**: Percentage of population living below poverty line
- **Poor_People_000s**: Number of poor people in thousands

#### Economic Indicators (Gross County Product)
- **GCP_2020_Ksh_Million**: Gross County Product 2020 in Ksh millions
- **GCP_2021_Ksh_Million**: Gross County Product 2021 in Ksh millions
- **GCP_2022_Ksh_Million**: Gross County Product 2022 in Ksh millions

#### Fourth Basis Parameter Indices
- **Population_Index_%**: County's share based on population (weight: 42%)
- **Equal_Share_Index_%**: Equal allocation to all counties (weight: 22%)
- **Poverty_Index_%**: County's share based on poverty levels (weight: 14%)
- **Income_Distance_Index_%**: Based on GCP per capita distance from Nairobi (weight: 13%)
- **Geographic_Size_Index_%**: Based on land area, capped at 10% (weight: 9%)

#### Allocation Calculations
- **Stabilisation_Factor**: Ensures no county receives less than FY 2024/25 allocation
- **Allocation_Factor_%**: Final percentage share for the county (sum of all weighted indices × stabilisation factor)

#### Financial Allocations
- **Third_Basis_2024_25_Allocation_Ksh_Million**: Allocation under previous (Third) basis for FY 2024/25
- **Fourth_Basis_2025_26_Allocation_Ksh_Million**: New allocation under Fourth Basis for FY 2025/26

### Total Allocations
- **FY 2024/25 Total**: Ksh 387.425 billion
- **FY 2025/26 Total**: Ksh 417.425 billion
- **Increase**: Ksh 30 billion (7.7% increase)

### Key Objectives
The Fourth Basis aims to:
1. **Share revenues equitably to facilitate service delivery** - Using population, equal share, and geographical size parameters
2. **Address economic disparities to promote development** - Using poverty and income distance parameters

### Top 5 Counties by 2025/26 Allocation
1. Nairobi City: Ksh 21.082 billion
2. Nakuru: Ksh 14.279 billion
3. Turkana: Ksh 13.805 billion
4. Kakamega: Ksh 13.562 billion
5. Kiambu: Ksh 13.094 billion

### Smallest 5 Counties by 2025/26 Allocation
1. Lamu: Ksh 3.935 billion
2. Tharaka-Nithi: Ksh 5.028 billion
3. Elgeyo-Marakwet: Ksh 5.374 billion
4. Embu: Ksh 5.616 billion
5. Kirinyaga: Ksh 5.693 billion

## Constitutional and Legal Framework

### Article 203(1) Criteria Applied
The Fourth Basis considers:
- (d) Ability of county governments to perform assigned functions
- (e) Fiscal capacity and efficiency of county governments
- (f) Developmental and other needs of counties
- (g) Economic disparities within and among counties
- (h) Need for affirmative action for disadvantaged areas
- (i) Need for economic optimization and revenue collection incentives
- (j) Desirability of stable and predictable allocations

### Implementation
- The Fourth Basis includes a stabilization factor to ensure no county receives less than FY 2024/25
- Valid for five financial years: 2025/26 through 2029/30
- Parliament approval received: September 2024

## Data Quality Notes
- All population data from official 2019 Kenya Population and Housing Census
- Poverty data from Kenya Poverty Report 2022 by KNBS
- GCP data from Gross County Product Report 2023 (KNBS)
- Geographic size from official KNBS records

## Usage
This dataset is suitable for:
- County budget planning and analysis
- Inter-county comparison studies
- Economic development research
- Public finance analysis
- Policy evaluation and planning

## Contact
Commission on Revenue Allocation
Prism Tower, 3rd Ngong Avenue, 28th Floor
P.O. Box 1310 – 00200, NAIROBI
Tel: +254-(020) 4298000 / 0709822000
Email: info@cra.go.ke
Website: www.cra.go.ke

## License
Public document - Government of Kenya

---
**Document Reference**: CRA 059
**Date Created**: January 2025
**Last Updated**: January 2025
