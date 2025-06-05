# iFood Marketing Campaign Analysis: Improve Campaign Conversion Rate by data-driven Customer Segmentation

# Project Background
iFood is Brazil's leading food ordering and delivery platform, holding over 80% market share as of 2021. Operating in the competitive food-tech industry, iFood has expanded beyond traditional food delivery to include non-comestible products such as gold and gadgets in their portfolio. The company generates revenue through commission fees, delivery charges, and advertising revenue from restaurant partners, with customer acquisition and retention being critical business metrics.

This analysis was conducted to support the marketing team's upcoming "Gadget Campaign" launch. The company's historical marketing campaigns have shown conversion rates between 7-8%, with some campaigns performing as low as 1%. However, a recent pilot campaign for a gadget achieved a promising 15.39% conversion rate from a random sample, indicating significant potential for optimization.

Insights and recommendations are provided on the following key areas:

- **Income Levels:** Impact of customer earnings on campaign acceptance rates
- **Household Composition:** How family structure affects purchasing behavior  
- **Segmentation Strategy:** Optimal customer targeting for maximum conversion rates

The Excel analysis files used to inspect and clean the data for this analysis can be found [here](https://github.com/Shree-Analyst/Marketing-Analytics-Project/tree/main/Resources).

Targeted analysis regarding customer segmentation and conversion optimization can be found in the methodology documentation [here]()

An interactive Excel dashboard with pivot tables and slicers used to explore customer segments can be found [here](https://github.com/Shree-Analyst/Marketing-Analytics-Project/blob/main/Resources/Charts/Super%20Pivot.png).

# Data Structure & Initial Checks

The company's customer database consists of a single comprehensive table containing customer and campaign interaction data, with a total of 2,021 records after data cleaning. The dataset encompasses 41 features covering multiple data categories:

- **Customer Demographics:** Age, income, education level, marital status, household composition
- **Behavioral Data:** Purchase history, complaint records, recency of last purchase, website visits
- **Campaign History:** Response rates to 5 previous marketing campaigns across different channels
- **Product Preferences:** Spending patterns across various product categories (wines, meat, fish, etc.)

The dataset contained primarily numerical variables (40 out of 41 features) with one categorical variable, making it well-suited for quantitative analysis and segmentation techniques.

# Executive Summary

### Overview of Findings

Analysis of iFood's customer base reveals that strategic demographic segmentation can more than double campaign conversion rates from 15.39% to 32.6%. The most effective customer segment consists of higher-income individuals (R$60,000+ annually) without children at home, representing 411 customers who show significantly stronger gadget purchase propensity. This segmentation strategy simultaneously reduces marketing costs through targeted outreach while dramatically improving campaign effectiveness, directly addressing iFood's goal of optimizing resource allocation and maximizing campaign profitability.

![Customer Segmentation Dashboard](https://github.com/Shree-Analyst/Marketing-Analytics-Project/blob/main/Resources/Charts/Super%20Pivot.png)

# Insights Deep Dive

### Income Levels Drive Campaign Success:

* **Higher income drives conversion.** Customers earning more than R$60,000 per year demonstrated significantly higher acceptance rates for the gadget campaign, suggesting that disposable income is a critical factor in non-essential product purchases.
  
* **Clear income threshold exists.** The R$60,000 annual income mark serves as a demarcation point, with customers above this threshold showing markedly different purchasing behaviors compared to lower-income segments.

![Income Brackets Analysis](https://github.com/Shree-Analyst/Marketing-Analytics-Project/blob/main/Resources/Charts/Insight%202%20-%20Income%20Brackets.png)

### Household Composition Creates Spending Differences:

* **Childless households show highest conversion.** Customers with no children at home accounted for over half of all campaign acceptants while representing only 25% of the total sample size, indicating a 2:1 over-representation in positive responses.
  
* **Discretionary spending advantage.** Households without children have more disposable income available for non-essential purchases like gadgets, as they're likely not allocating resources toward child-related expenses.

![Children at Home Analysis](https://github.com/Shree-Analyst/Marketing-Analytics-Project/blob/main/Resources/Charts/Insight%201%20-%20Children%20at%20home.png)

### Optimal Segmentation Balances Conversion and Scale:

* **Best segment identified.** The combination of high income (R$60k+) and no children creates the most effective customer segment with 32.6% conversion rate and sufficient sample size (411 customers).
  
* **Scale vs. precision trade-off.** While further segmentation by marital status could achieve 47.27% conversion rates, it reduces the sample to only 165 customers, potentially making the metric less reliable for broader application.

![Marital Status Analysis](https://github.com/Shree-Analyst/Marketing-Analytics-Project/blob/main/Resources/Charts/Insight%203%20-%20Marital%20Status.png)

# Recommendations:

Based on the insights and findings above, we would recommend the Marketing Team to consider the following: 

* **Target high-income, childless customers for the Gadget Campaign.** Focus marketing spend on customers earning R$60,000+ with no children to achieve 32.6% conversion rates while maintaining a robust sample size of 411 customers.
  
* **Implement demographic-based segmentation across campaigns.** Replace broad-based marketing approaches with targeted customer segmentation to reduce costs and improve effectiveness beyond the current 15.39% baseline.
  
* **Reserve ultra-narrow segments for specific use cases.** While segments combining income, children, and marital status achieve higher conversion (47.27%), their small audience size (165 customers) makes them suitable only for premium product launches or test campaigns.
  
* **Apply segmentation learnings to broader product portfolio.** Extend these demographic insights to other categories in iFood's expanding product range for consistent targeting improvements.

# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* The pilot campaign sample of 15.39% conversion rate is assumed to be representative of the broader customer base, though confidence intervals were not established to validate this assumption.
  
* Customer demographic and behavioral data is assumed to be current and accurate, though the dataset's collection date and potential data quality issues were not independently verified.
  
* Income thresholds are based on Brazilian Real (R$) values from the dataset's time period and may not reflect current economic conditions or purchasing power changes due to inflation.
  
* The analysis assumes that gadget preferences remain consistent across the identified demographic segments and doesn't account for potential product-specific preferences within the broader "gadget" category.
