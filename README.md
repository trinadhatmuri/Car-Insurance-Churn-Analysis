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
  <img src="https://github.com/user-attachments/assets/6cb1238e-39f4-46af-a9f4-cc1c75abe10d" alt="2022 acquisition with avg" width="1000" height="452" style="display: block;" />
  <strong>December 2021 - November 2022</strong>
</p>







