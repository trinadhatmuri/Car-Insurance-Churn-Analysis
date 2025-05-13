# Car-Insurance-Churn-Analysis
## Table of Contents
1. Background and overview.
2. Datastructure overview.
3. Executive summary.
4. Insights deep dive.
5. Recommendations.

## Background and Overview
  This project focuses on analyzing customer churn patterns for a fictinal company nextGen Insurance Inc. The data available is synthetically generated to simulate real world auto insurance data and includes variables such as
  <ul>
    <li>Customer demographics (age, gender, marital status etc)</li>
    <li>Policy details (tenure, yearly premium, date joined)</li>
    <li>Customer churn indicator (whether the customer left or stayed)</li>
  </ul>

  This analysis aims to:
  <ul>
    <li>Explore key factors influencing churn</li>
    <li>Visualize churn trends across different demographics</li>
    <li>Calculate churn rate and customer lifetime value metrics</li>
    <li>Propose actionable solutions for improving retention strategies</li>
  </ul>

  An interactive Tableau dashboard can be viewed here <a href="https://public.tableau.com/app/profile/trinadh.atmuri/viz/Book1_17463238783600/CarInsuranceChurnDashboard">Link</a>

## Datastructure Overview

<img width="725" alt="ER diagram" src="https://github.com/user-attachments/assets/f71b6551-53cb-49f4-9b4d-ae7015ffbed2" />

## Executive Summary

The analysis shows a 100% churn rate, with over 15,000 customers lost monthly and only four months where acquisitions exceeded churn for the time period December 2021 - November 2022. The customer base is older, with 66% over age 50, and nearly half have a tenure of one year or less. These trends highlight urgent issues in acquisition and retention. We will explore these challenges further and outline key areas for improvement in the following sections.

<img width="1000" alt="Dashboard" src="https://github.com/user-attachments/assets/b4d19489-90de-4256-a3c1-2faa0a8627f7" />

## Insights Deep Dive

2022 has been a year of major changes for nextGen Insurance, starting from major policy changes to allocating higher marketing budgets had a significant impact on the insurance. 

### Acquisitions
<ul>
  <li>The average number of acquisitions over the last 5 years (2016 to 2021) was 5840 acquisitions, which sky rocketed to 7433 acquisitions per month in 2022.</li>
  <li>If we look at the 5 year graph closely, we can see that from December 2016 to October 2019 the number of monthly acquisitions have been closely following the average line while once a year there is one peak month in the 2nd half of the year where the number of acquisitions at least doubles.</li>
  <li>From November 2019 we can see a downward trend which starts its revival from May 2021. In the timeline of this downward trend, we can only see two months which are above the average in the 2nd half of 2020. The average number of acquisitions for years 2019-2021 is down to 4542 compared to a healthy average acquisitions over a 5-year period.</li>
  <li>For the current year (December 2021- November 2022) the average acquisitions is a whopping 19611 per month as a result of increased budget for marketing campaigns and introducing new customer offers from May 2022 to September 2022 which resulted in over 35k acquisitions for four month in a row. The data for November is incomplete and can be left out.</li>
</ul>


<p align="center">
  <img src="https://github.com/user-attachments/assets/3f98fe18-a151-45b2-8abd-9efd37c9247e" alt="2019-21 acquisitions with avg" width="1009" height="470" style="display: block;" />
  <strong>November 2019 - November 2021</strong>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d8aba9b7-c077-4613-b9df-4356e4587966" alt="5 year acquisition with avg" width="1001" height="490" style="display: block;" />
  <strong>December 2016 - November 2021</strong>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/6cb1238e-39f4-46af-a9f4-cc1c75abe10d" alt="2022 acquisition with avg" width="1000" height="400" style="display: block;" />
  <strong>December 2021 - November 2022</strong>
</p>


### Churned Customers:

<ul>
  <li>This analysis covers the churn data from December 2021 to November 2022.</li>
  <li>The graph shows that for the given period each month saw a consistent churn of over 15,000 customers, highlighting a sustained attrition issue.</li>
  <li>The 45–55 age group emerged as the largest segment among churned customers, pointing to a demographic pattern in customer departures.</li>
  <li>It can also be noted that there is a high risk that a customer can churn within the first year. When we compare the Tenure with the insurance and the Age bins, we can clearly see that majority of the churned customers have an age of 50 or above and below 1 year with the insurance.  </li>
</ul>

<div align="center">
  <img src="https://github.com/user-attachments/assets/5fb7f69c-7f66-4cae-9921-b7f452862abb" width="800" alt="Churn by Age" />
  <div><strong>Churn by Age</strong></div>
</div>

<br>

<div align="center">
  <img src="https://github.com/user-attachments/assets/0d10eaac-2458-40eb-a175-25763a1392ad" width="800" alt="Churn for Tenure 0, 1 and 17 Years" />
  <div><strong>Churn for Tenure 0, 1 and 17 Years</strong></div>
</div>

### Demographics:

<ul>
  <li>Churn rates appear to be higher in the income brackets of $50,000 to $100,000, with the most churned customers in the income range of $87,500 to $125,000.</li>
  <li>Customers who own homes show a significantly higher churn rate compared to non-homeowners, with a large percentage of churned customers in the income range of $100,000 to $150,000.</li>
  <li>Churned customers with higher education (college degree) show a higher churn rate, especially in income brackets above $50,000.</li>
  <li>Churned customers with good credit also show a higher churn rate, particularly in the income ranges above $50,000.</li>
</ul>

<p align="center">
  <img width="977" alt="Demo stats" src="https://github.com/user-attachments/assets/d9795ba2-444d-41cf-98fa-f40fb5eb768d" />
  <strong>Demographic Statistics</strong>
</p>

<p align="center">
  <img width="977" alt="income vs churn" src="https://github.com/user-attachments/assets/5fa747c0-6ba6-4c3b-a24e-e187c6c518b6" />
  <strong>Churn by Income Levels</strong>
</p>


### Recommendations:

Based on the uncovered insights, the following recommendations are provided:

<ul>
  <li>Introduce structured engagement programs (welcome kits, regular policy reviews, loyalty incentives) focused on new customers in their first 12 months, as this group shows the highest churn risk.</li>
  <li>Develop tailored insurance products and communication for the 45–55 age group, the highest-churning segment, focusing on their needs like health benefits, retirement support, and family protection plans.</li>
  <li>Since most churn occurs in the $85,000–$125,000 income range, evaluate whether pricing or benefits within this tier align with customer expectations. Consider introducing mid-tier flexible plans or added-value services.</li>
  <li>Invest in educating new customers—especially those with college degrees and good credit—about the long-term benefits of their policy, usage options, and additional perks, to reduce early dissatisfaction and churn.</li>
  <li>Rather than maximizing volume, recalibrate marketing strategies to attract individuals with historically higher retention patterns, such as those under 45 or with longer residential tenure, to improve long-term profitability.</li>
</ul>

