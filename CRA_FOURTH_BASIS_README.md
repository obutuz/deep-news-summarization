# CRA Fourth Basis for Revenue Sharing Among Counties (2025/26 - 2029/30)

## Overview
This dataset contains the complete revenue sharing allocation framework for Kenya's 47 county governments for the financial years 2025/26 to 2029/30, as recommended by the Commission on Revenue Allocation (CRA).

## Data Source
- **Document**: CRA-The-Fourth-Basis-for-revenue-sharing-among-counties-2025-2030.pdf
- **Authority**: Commission on Revenue Allocation (CRA), Kenya
- **Publication Date**: December 2024
- **Coverage Period**: Financial Years 2025/26 to 2029/30 (5 years)
- **Legal Basis**: Constitution of Kenya 2010, Article 216(1)(b) and Article 217

## Revenue Sharing Formula

The Fourth Basis uses a **two-objective framework**:

### Objective 1: Share revenues equitably to facilitate service delivery
- **Population** (42%) - Based on 2019 Census data
- **Equal Share** (22%) - Minimum allocation to all counties
- **Geographical Size** (9%) - Based on land area in square kilometers

### Objective 2: Address economic disparities and promote development
- **Poverty** (14%) - Based on poverty headcount rate (Kenya Poverty Report 2022)
- **Income Distance** (13%) - Based on Gross County Product (GCP) per capita

### Formula
```
County Allocation = (0.42 × Population Index + 0.22 × Equal Share Index +
                     0.14 × Poverty Index + 0.09 × Geographic Size Index +
                     0.13 × Income Distance Index) × Stabilisation Factor
```

### Stabilisation Factor
An inbuilt mechanism ensures no county receives less than their FY 2024/25 allocation, providing budget stability and predictability.

## Files Included

### 1. cra_fourth_basis_revenue_sharing_2025_2030.csv
**Complete county allocation data including:**
- County demographic data (population, poverty rates, geographic size)
- Economic data (Gross County Product 2020-2022)
- All five parameter indices (Population, Equal Share, Poverty, Income Distance, Geographic Size)
- Stabilisation factors
- Allocation percentages
- Third Basis FY 2024/25 allocations (for comparison)
- Fourth Basis FY 2025/26 allocations

**Columns:**
- County: Name of the county
- Population_2019: Population from 2019 Census
- Poverty_Rate_%: Poverty headcount rate (%)
- Poor_People_000s: Number of poor people (thousands)
- GCP_2020/2021/2022_Ksh_Million: Gross County Product at current prices
- Geographic_Size_Sq_Kms: Land area in square kilometers
- Population_Index_%: Weighted population allocation index
- Equal_Share_Index_%: Equal share allocation index
- Poverty_Index_%: Poverty-based allocation index
- Income_Distance_Index_%: Income distance allocation index
- Geographic_Size_Index_%: Geographic size allocation index
- Stabilisation_Factor: Stabilisation adjustment factor
- Allocation_Factor_%: Final allocation percentage for each county
- Third_Basis_2024_25_Ksh_Million: FY 2024/25 allocation (Third Basis)
- Fourth_Basis_2025_26_Ksh_Million: FY 2025/26 allocation (Fourth Basis)

### 2. cra_fourth_basis_formula_parameters.csv
**Summary of the five parameters:**
- Parameter objectives
- Weights assigned to each parameter
- Descriptions and data sources

### 3. cra_fourth_basis_projections_2025_2030.csv
**Projected allocations for all 5 years (2025/26 to 2029/30)**
- Based on allocation indices from the Fourth Basis
- Future year projections assume revenue growth rates

## Key Highlights

### Total Allocations
- **FY 2024/25 (Third Basis)**: Ksh 387.425 Billion
- **FY 2025/26 (Fourth Basis)**: Ksh 417.425 Billion
- **Increase**: Ksh 30.0 Billion (7.7% growth)

### Top 5 County Allocations (FY 2025/26)
1. **Nairobi City**: Ksh 21.082 Billion (5.05%)
2. **Nakuru**: Ksh 14.279 Billion (3.42%)
3. **Turkana**: Ksh 13.805 Billion (3.31%)
4. **Kakamega**: Ksh 13.562 Billion (3.25%)
5. **Kiambu**: Ksh 13.094 Billion (3.14%)

### Counties with Largest Increases (FY 2024/25 to 2025/26)
1. **Garissa**: +Ksh 2.604 Billion (+31.4%)
2. **Marsabit**: +Ksh 1.830 Billion (+24.1%)
3. **Wajir**: +Ksh 1.380 Billion (+13.9%)
4. **Kajiado**: +Ksh 1.422 Billion (+17.0%)
5. **Isiolo**: +Ksh 1.317 Billion (+26.7%)

### Major Changes from Third to Fourth Basis

**Framework Shift:**
- **Third Basis**: Functional/sectoral approach (Health 17%, Agriculture 10%, Roads 8%, etc.)
- **Fourth Basis**: Expenditure proxy approach (Population, Equal Share, Geographic Size, Poverty, Income Distance)

**Key Improvements:**
1. Eliminated multiple uses of population-based measures
2. Simplified from 8 parameters to 5 core parameters
3. Increased population weight from 18% to 42%
4. Introduced economic optimization incentive (Income Distance 13%)
5. Removed unstable fiscal effort measures
6. Maintained stabilisation mechanism for budget predictability

## Data Quality & Sources

All underlying data sourced from official government statistics:
- **Population**: Kenya Population and Housing Census 2019 (KNBS)
- **Poverty**: Kenya Poverty Report 2022 (KNBS)
- **Economic Data**: Gross County Product Report 2023 (KNBS)
- **Geographic Data**: Kenya National Bureau of Statistics

## Usage Notes

1. **Allocation Indices are Fixed**: The allocation percentages (Allocation_Factor_%) remain constant throughout the 5-year period
2. **Actual Amounts Vary**: Total revenue available each year determines absolute allocations
3. **Minimum Protection**: No county can receive less than FY 2024/25 allocation (Stabilisation Factor)
4. **Annual Approval**: Parliament approves specific amounts annually through County Allocation of Revenue Acts (CARA)

## Constitutional Basis

The Fourth Basis adheres to **Article 203(1)** criteria:
- **(d)** Ability to perform assigned functions
- **(e)** Fiscal capacity and efficiency
- **(f)** Developmental needs
- **(g)** Economic disparities and remedies
- **(h)** Affirmative action for disadvantaged areas
- **(i)** Economic optimization incentives
- **(j)** Stable and predictable allocations

## Future Years (2026/27 - 2029/30)

The Fourth Basis framework will apply for all 5 years. Actual allocations depend on:
- Total nationally raised revenue
- Division of Revenue between National and County governments
- Economic growth and revenue performance
- Parliamentary approval of annual CARA

## References

1. Commission on Revenue Allocation (2024). "Recommendation Concerning the Fourth Basis for Revenue Sharing Among County Governments for Financial Years 2025/26 - 2029/30"
2. Constitution of Kenya 2010, Articles 203, 216, 217
3. Kenya National Bureau of Statistics - Kenya Population and Housing Census 2019
4. Kenya National Bureau of Statistics - Kenya Poverty Report 2022
5. Kenya National Bureau of Statistics - Gross County Product Report 2023

## Contact & More Information

- **CRA Website**: https://cra.go.ke
- **Parliament of Kenya**: https://www.parliament.go.ke
- **KNBS**: https://www.knbs.or.ke

---
*Dataset compiled from CRA Fourth Basis document dated December 2024*
*Last Updated: November 2025*
