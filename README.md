# GLOBOX A/B Experiment Project Portfolio

## Project Overview

This portfolio demonstrates an end-to-end A/B Testing analysis conducted for the Food and Drink banner design on the landing page of GLOBOX's e-commerce mobile application.
The primary goal was to evaluate whether the new banner significantly impacts user behavior and increases key business metrics, including revenue, feasibility, and product awareness.

## Contents
<ol>
<li>Project Context</ol>

<li>Data Extraction and Preparation</ol>

<li>Methodology and Analysis</ol>

<li>Results and Interpretation</ol>

<li>Insights and Recommendations</li>

<li>Additional Resources</li>
</ol>

## Project Context

GLOBOX, recognized for boutique fashion and decor, has expanded into food and drink categories. To enhance visibility and sales, an A/B experiment was implemented comparing:
<ul>
<li>Group A (Control): Existing app design without banner.</li>

<li>Group B (Treatment): New design featuring the food and drink banner.</li>

Experiment Duration: January 25, 2023 – February 6, 2023
</ul>

## Data Extraction and Preparation

Data were collected from GLOBOX’s database and structured through SQL extraction, transforming three main tables:
<ul>
<li>Users: User demographics.</li>

<li>Groups: A/B test assignments.</li>

<li>Activity: User purchasing records.</li>
</ul>
SQL scripts used for data extraction and transformation are documented and provided here.

## Methodology and Analysis

Analytical methods included:
<ul>
  
<li>Hypothesis Testing:</li>
<ul>
<li>Conversion Rate (Two-sample Z-test)</li>

<li> Amount Spent (Two-sample T-test)</li>
</ul>
<li>Confidence Interval Calculation</li>

</li>Data Visualization using Tableau ([Dashboard Link](https://public.tableau.com/app/profile/chukwuemeka.isaac.anyakwu/viz/GloboxProjectChuksIsaac/Globox?publish=yes))</li>
</ul>
Key metrics were compared across demographics, device types, and geographic regions.

## Results and Interpretation
<ul>
<li>Conversion Rate: Significant increase in Group B (Treatment) compared to Group A (Control). (p-value = 0.0001)</li>

<li>Average Amount Spent: No significant difference detected between groups. (p-value = 0.944)</li>

<li>Confidence Interval: Reinforced the statistical significance of the conversion rate increase (0.35% - 1%).</li>
</ul>
Further insights were derived based on gender, device type, and geographical regions, highlighting opportunities for targeted marketing strategies.

## Insights and Recommendations

Based on the analysis:
<ul>
<li>Recommendation: Proceed with launching the Food and Drink banner to leverage significant improvements in conversion rates.</li>

</li>Further Analysis: Monitor longer-term effects and continue experimentation, especially focusing on average spending trends.</li>

Tailor marketing strategies according to insights gained from gender and device-specific behaviors.</li>
</ul>

## Additional Resources
<ul>
  
<li>Comprehensive A/B Experiment Report</li>

<li>Video Presentation</li>

<li>Excel Data Analysis File</li>

<li>SQL Data Extraction Queries</li>

<li>Tableau Visualizations Dashboard</li> </ul>

