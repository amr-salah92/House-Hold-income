## Table of Contents
1. [Project Name](#project-name)
2. [Project Background](#project-background)
3. [Project Goals](#project-goals)
4. [Insights and Recommendations](#insights-and-recommendations)
   - [Category 1: Income vs. Expenses](#category-1-income-vs-expenses)
   - [Category 2: Family Size and Financial Stability](#category-2-family-size-and-financial-stability)
   - [Category 3: Education and Earnings](#category-3-education-and-earnings)
   - [Category 4: Savings and Future Planning](#category-4-savings-and-future-planning)
5. [Data Structure & Initial Checks](#data-structure-initial-checks)
6. [Executive Summary](#executive-summary)
7. [Insights Deep Dive](#insights-deep-dive)
   - [Category 1: Income vs. Expenses](#category-1-income-vs-expenses)
   - [Category 2: Family Size and Financial Stability](#category-2-family-size-and-financial-stability)
   - [Category 3: Education and Earnings](#category-3-education-and-earnings)
   - [Category 4: Savings and Future Planning](#category-4-savings-and-future-planning)
8. [Recommendations](#recommendations)
9. [Technical Details](#technical-details)
10. [Assumptions and Caveats](#assumptions-and-caveats)

## Project Name
**Household Income and Expense Analysis**

## Project Background
This analysis examines household financial data, focusing on income, expenses, and financial stability metrics. The dataset includes records from 50 households, detailing monthly and annual income, number of family members, rent or EMI payments, and educational qualifications. Understanding these factors can provide insights into financial health and potential economic challenges faced by different households.

## Project Goals
The primary objectives of this analysis are:
- To understand household income distribution and expenditure patterns.
- To assess financial stability by comparing expenses to income.
- To explore the relationship between educational qualifications and earning members.
- To identify trends that can inform financial planning strategies.

## Insights and Recommendations

### Category 1: Income vs. Expenses
- **Main Insight 1:** Households with a single earning member tend to have higher expenses relative to income.
- **Main Insight 2:** Rent/EMI payments significantly impact disposable income.
- **Main Insight 3:** Higher-educated households tend to have higher income levels.
- **Main Insight 4:** Some households exhibit negative savings, indicating financial distress.

![Impact of expense on Income According to Number of earners ](https://github.com/user-attachments/assets/164f5e4a-7687-40c8-b9dc-2b9cd4c0800d)


### Category 2: Family Size and Financial Stability
- **Main Insight 1:** Larger households often have higher expenses but not necessarily higher income.
- **Main Insight 2:** Families with multiple earning members tend to have lower financial strain.
- **Main Insight 3:** Rent/EMI payments are more burdensome for single-income families.
- **Main Insight 4:** Financial stability improves with diversified income sources.




### Category 3: Education and Earnings
- **Main Insight 1:** Graduate-level education correlates with higher household income.
- **Main Insight 2:** Illiterate households report lower earnings and higher expense burdens.

![Impact of Rent on Income According to Education Levels](https://github.com/user-attachments/assets/202fb9c1-3306-41e3-9742-57848691fbac)

  
- **Main Insight 3:** Undergraduates have varied earnings depending on household size.
- **Main Insight 4:** Education level affects the number of earning members in a household.
  

![Number of Earners according to education level](https://github.com/user-attachments/assets/15bd7d49-f997-42d9-8fe1-8abe16371ffd)

### Category 4: Savings and Future Planning
- **Main Insight 1:** Households with low EMI/Rent have better savings potential.
- **Main Insight 2:** Households with a single earning member struggle with savings.
- **Main Insight 3:** Higher education correlates with better financial planning.
- **Main Insight 4:** Some high-income households still exhibit poor savings behavior.


![Saving according to Number of earners](https://github.com/user-attachments/assets/ae134988-9c76-4a1f-88e6-02b630ab47f0)


## Data Structure & Initial Checks
The dataset consists of the following columns:


| Column                    | Description                        |
|---------------------------|------------------------------------|
| `Mthly_HH_Income`         | Monthly Household Income           |
| `Mthly_HH_Expense`        | Monthly Household Expenses         |
| `No_of_Fly_Members`       | Number of Family Members           |
| `Emi_or_Rent_Amt`         | Monthly EMI or Rent Amount         |
| `Annual_HH_Income`        | Annual Household Income            |
| `Highest_Qualified_Member`| Highest Qualification in Household |
| `No_of_Earning_Members`   | Number of Earning Members          |

![Screenshot_1-2-2025_181252_dbdiagram io](https://github.com/user-attachments/assets/06964b2f-4da3-4422-8b47-e99738b19b07)

## Executive Summary
This analysis reveals key insights about household financial stability. Households with multiple earning members generally exhibit lower financial strain, while single-income families face higher expenses relative to income. Education plays a significant role in earnings potential, and EMI/Rent payments significantly affect savings potential. These findings can inform policies to improve financial planning and support systems for vulnerable households.

## Recommendations
- Encourage financial literacy programs for lower-educated households.
- Promote multi-income streams to improve financial stability.
- Reduce EMI/Rent burden through better housing finance options.
- Support education initiatives to improve long-term earning potential.

## Technical Details
This analysis was conducted using Excel (Power Query for data processing) [Book1.xlsx](https://github.com/user-attachments/files/18629570/Book1.xlsx) 
and an interactive Tableau dashboard provides deeper insights. You can explore the Tableau dashboard [here](https://public.tableau.com/views/HouseholdAnalysisDashboard/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Assumptions and Caveats
- Missing values in education were assumed to be "Illiterate."
- Some outliers in income and expenses were excluded for better trend analysis.
- Households with zero EMI/Rent were assumed to own their residence.
- Small sample size (50 households) may not represent broader economic trends.
