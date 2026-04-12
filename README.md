# unicef-child-nutrition-report
A  Quarto-based data analytics report analysing global child nutrition patterns using UNICEF datasets, including visualisations of consumption trends, country comparisons, and geographic distribution.
Table of contents
Introduction
Countries Most Affected by Poor Fruit and Vegetable Consumption
Countries Most Affected by Poor Fruit and Vegetable Consumption
Relationship Between Boys’ and Girls’ Nutrition Outcomes
Global Trend in Poor Fruit and Vegetable Consumption
Global Distribution of Child Nutrition Risk
Conclusion
Global Child Nutrition Patterns: Fruit and Vegetable Consumption Among Children Aged 6–23 Months (2005–2024)
Author
Sreeju Sreedharan

Latest year: 2024
Rows in latest_df: 3
Introduction
Child nutrition is a major global public health concern, especially during the first two years of life when dietary diversity is critical for healthy growth and development. Fruits and vegetables provide essential micronutrients that support immunity, physical development, and cognitive health.

This report analyses UNICEF data on fruit and vegetable consumption among children aged 6–23 months between 2005 and 2024. The goal is to identify where poor dietary diversity is most severe, how patterns have changed over time, and whether differences appear across sex and geography.

The analysis uses four visualisations: a bar chart, a scatterplot with a regression line, a time-series chart, and a world map. Together, they tell a clearer story about global child nutrition inequality and the continuing challenge of ensuring healthy diets for young children.

Countries Most Affected by Poor Fruit and Vegetable Consumption
This chart highlights the countries with the highest levels of poor fruit and vegetable consumption among children in the most recent year available. It helps identify where nutrition risks are most concentrated and where targeted intervention may be most urgently needed.

Countries Most Affected by Poor Fruit and Vegetable Consumption
This chart shows the countries with the highest average levels of poor fruit and vegetable consumption among children aged 6–23 months across the available years in the UNICEF dataset.

         country  obs_value
36        Guinea  76.511111
29      Ethiopia  75.625000
88         Sudan  66.966667
107        Yemen  65.500000
85       Somalia  65.100000
32        Gambia  65.066667
10        Bhutan  60.866667
0    Afghanistan  59.800000
17          Chad  59.093333
73      Pakistan  58.700000


Relationship Between Boys’ and Girls’ Nutrition Outcomes
This scatterplot compares country-level rates of poor fruit and vegetable consumption for boys and girls. Each point represents a country, and the regression line highlights the strength of the relationship between the two groups.



Global Trend in Poor Fruit and Vegetable Consumption
This time-series chart illustrates how global levels of poor fruit and vegetable consumption among children have changed between 2005 and 2024. It helps identify whether dietary diversity has improved or worsened over time.



Global Distribution of Child Nutrition Risk
This map shows the geographic distribution of poor fruit and vegetable consumption among children. Darker shades represent higher levels of poor dietary intake, helping identify regional clusters of nutrition risk.

Countries in dataset: 110
Matched countries: 89


Conclusion
This analysis highlights clear inequalities in fruit and vegetable consumption among children aged 6–23 months across countries and over time. The results show that several countries continue to report high levels of poor dietary diversity, indicating persistent nutritional challenges that affect early childhood development.

The bar chart identified the countries with the highest average levels of poor fruit and vegetable consumption, suggesting where intervention efforts may be most urgently needed. The time-series analysis revealed how global dietary patterns have evolved over the years, providing insight into whether nutrition outcomes are improving or stagnating. The scatterplot comparing male and female outcomes showed that poor dietary patterns often affect both groups similarly, indicating that national-level food access and nutrition systems play a significant role. Finally, the world map visualised the geographical distribution of nutrition risks, highlighting regional clusters where poor dietary intake is more common.

Overall, this report demonstrates that improving child nutrition remains a global priority. Continued investment in public health programs, food access initiatives, and education around healthy diets is essential to ensure better nutritional outcomes for children worldwide.

pandoc 
  to: html
  output-file: unicef_report.html
  standalone: true
  embed-resources: true
  section-divs: true
  html-math-method: mathjax
  wrap: none
  default-image-extension: png
  toc: true
  
metadata
  document-css: false
  link-citations: true
  date-format: long
  lang: en
  title: 'Global Child Nutrition Patterns: Fruit and Vegetable Consumption Among Children Aged 6–23 Months (2005–2024)'
  author: Sreeju Sreedharan
  theme: cosmo
  
Output created: unicef_report.html
