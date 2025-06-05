# Working Title: iFood Data Analyst Business Case (Part 1)
**Background:** iFood is Brazil's leading food ordering & delivery platform, holding over 80% market share as of 2021. As part of their hiring process in 2020 before the pandemic, a business case was sent out to potential candidates. A dataset was made available by a GitHub contributor, presumably a candidate. More information about this business case can be found [here](https://github.com/nailson/ifood-data-business-analyst-test/tree/master). Project walkthrough follows below.

**Alerts:**
1. A more updated version of this case incorporating more advanced analytics may be available. Be sure to click on the most recent version in my portfolio!
2. For a simpler, concise walkthrough, consult the video version of this case by following this link.

## Project Overview
**Business Problem:** iFood has a few non-comestible products in their portfolio, such as gold and gadgets. The company would like to launch a marketing campaign for a gadget. This is termed as "Gadget Campaign". The conversion rates of iFood's past 5 marketing campaigns have been around 7-8% with one campaign generating rates as low as 2%. To test out the gadget campaign, the company selected a random sample from their campaign database for a pilot campaign which generated a conversion rate of 15.39%. It would like to understand how to further optimise campaign results & generate value for the company.
Keeping the outcome of "increase conversion rate for Gadget Campaign" in mind, the following business reseach question was selected: **How can iFood effectively segment its customers to increase the conversion rate of the Gadget Campaign?**
This research question provides 2 analysis goals: reduce target population size, increase acceptance rates.

**Dataset:** The company provided a sample dataset that mocks metainformation on customers and their interaction with the company's past marketing campaigns. The data contained customer demographic information (age, income, marital status, children at home) and behavioural information (complaints, recency, response to marketing campaigns, channels frequented, etc.) across 41 features, all but 1 numerical. After cleaning, 2021 unique records remained.

**Tools Used & Methodology:** This project was entirely completed in Microsoft Excel using functions (COUNTIFS, SUMIFS, etc.), charts, and pivot tables + slicers. For a relatively and clean small dataset, advanced scraping or querying was not required. Moreover, the project scope involved identifying trends rather than hypothesis testing. Therefore, descriptive statistics and data visualisation using Excel were deemed sufficient to answer this business question. A step-by-step breakdown of methodology is available in the project folder.

**Key Insights & Business Recommendations:** Analysis found 3 key insights summarised by graphs below -
1. Number of children at home - Customers with no children in their household accounted for over half of campaign accpetants while only making up a quarter of the sample size.
2. Income - Customers earning more than R$60,000 per year made up a greater share of campaign acceptants.
3. Marital status - Customers who were reportedly together or married showed poorer acceptance rates than those who were single, divorced, or widowed.

The key business recommendation to be followed is therefore:
**For the Gadget Campaign, iFood should target customers who earn R$60k and above, with no children in their household.** This increases the campaign's conversion rate to 32.6% while leaving a sample size large enough (411) for the metric to be close to the actual value. This recommendation was presented in an interactive Pivot table as shown below.

Following this recommendation will enable iFood to run a profitable marketing campaign by requiring fewer resources and generating more conversions.

Further eliminating customers who are married & together improves the conversion rate to 47.27%, but drastically reduces the sample size to 165. To keep the real value of the conversion rate as close to the sampled metric as possible, a larger sample size is desirable. Therefore, a conversion rate of 32.6% with a sample size of 411 is deemed optimum for this project.

**Limitations and Next Steps:** Importantly, this analysis does not establish confidence intervals. The real metric value, therefore, will be different from the 32.6%. Therefore, it is imperative to enlarge the sample size as much as possible while segmenting customers.

Next steps can include -
1. Establishing confidence intervals for conversion rate using various customer segments.
2. Investigating how various conversion rates affect campaign's profitability.
3. Creating simpler, more accessible dashboards to summarise the business's current picture and future recommendations using visualisation tools like Tableau, Looker, or PowerBI.

### Sources
[Medium - Measurable AI](https://medium.com/measurable-ai/2021-brazil-food-delivery-ifood-continues-to-lead-with-over-80-market-share-9eaa8b3cb954)
[GitHub Contributor](https://github.com/nailson/ifood-data-business-analyst-test/tree/master)
