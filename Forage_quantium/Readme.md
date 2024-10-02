# Quantium Data Analytics Virtual Experience with Forage

## Problem Statement
- Data preparation and customer analytics
- Experimentation and uplift testing
- Analytics and commercial application

## Dependencies
Language: Python 3.8
Packages: pandas, matplotlib, mlxtend, datetime, sklearn, scipy

### Task 1: Data Preparation and Customer Analytics
This task involved preparing and analyzing customer data from QVI_purchase_behaviour.csv and QVI_transaction_data.xlsx. Data cleaning was performed by converting date formats to datetime and removing outliers and errors.
The analysis focused on purchase behaviors across various customer segments, categorized by LIFESTAGE and MEMBER_TYPE. Key findings include:
- The top three sales-generating segments are Budget Older Families, Mainstream Young Singles/Couples, and Mainstream Retirees.
Mainstream Young Singles/Couples comprise the largest population, while Older Families have the highest average packets purchased per customer.
- Kettles chips and 175g packets are consistently popular across segments.
- Notably, Mainstream Young Singles/Couples show a strong preference for Tyrells chips (28% more likely) and 270g Twisties packets (32% more likely).

#### Insights :
- Budget-conscious Older Families, Young Singles/Couples, and Retirees drive the majority of sales.
- Young Singles/Couples are the largest demographic, with Older Families buying more packets per customer.
- Kettles and 175g packets are clear favorites, but Young Singles/Couples stand out with a preference for premium Tyrells chips and larger 270g Twisties packets.

### Task 2: Experimentation and Uplift Testing
This task involved evaluating the impact of a new store layout on sales performance. Three stores (77, 86, 88) underwent layout changes during Feb-Apr 2019, serving as trial locations.
Methodology:
- Utilized QVI_data.csv to analyze total sales and customer count metrics.
- Calculated a combined score for trial and potential control stores using Pearson correlations and magnitude distances.
- Conducted hypothesis testing to determine if differences in performance metrics between control stores (highest-scoring stores) and trial stores were statistically significant.

#### Insights :
##### Control-Trial Store Pairs Analysis
##### The analysis of control-trial store pairs yielded the following results:
###### Store 77 (trial) vs. Store 233 (control):
- Statistically significant increase in total sales in March and April (above 95% threshold).
- Significant increase in customer count in at least two months.
###### Store 86 (trial) vs. Store 155 (control):
- Significant increase in total sales in March.
- Significant increase in customer count in at least two months.
###### Store 88 (trial) vs. Store 40 (control):
- No statistically significant change in performance due to the trial.

### Task 3: Analytics and commercial application
Prepared a comprehensive PowerPoint report synthesizing key findings from Tasks 1 and 2, utilizing the Pyramid Principle to effectively communicate insights.
