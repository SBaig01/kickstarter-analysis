# Kickstarting with Excel

## Overview of Project

### Purpose
Louise did not meet her fundraising target for her play Fever despite coming close to it. This analysis was conducted for Lousie to identify any trends in how different campaigns fared in relation to their launch dates and their funding goals to derive additional insights.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The following graph shows the possible relation between successful, failed and canceled campaign outcomes (for other campaigns) compared to their respective launch dates. 

![Theater_Outcomes_vs_Launch](https://github.com/SBaig01/kickstarter-analysis/blob/d21d898dbb1c6fb7a306d32a55cf2026d6462d61/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

The following graph shows the possible relation between successful, failed and canceled campaign outcomes (for other campaigns) compared to their pre-defined funding goals (expressed as a percentage).

![Outcomes_vs_Goals](https://github.com/SBaig01/kickstarter-analysis/blob/e36710ca997fda482d7675e6e94ffcc172b62b2e/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
* CountIfs formula needed to include the criteria for Outcome. We could not simply fiCmlter in the Kickstarter datasheet to get appropriate numbers in Outcomes Based on Goals.
* Since there were no Cancelled plays in the dataset, a manual review of data in the Kickstarter datasheet was needed to validate if the CountIfs formula were working as expected.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. Most successful campaigns were launched around May-June-July timeframe.
  2. The least successful campaigns were launched around Nov-Dec-Jan timeframe.

- What can you conclude about the Outcomes based on Goals?
  * The higher the target, the more likely the campaign will fail.

- What are some limitations of this dataset?
  1. The dataset does not provide the play genre, which might have provided additional insights for Lousie.
  2. The dataset does not exclude any outliers, which might be skewing our results/analyses. 

- What are some other possible tables and/or graphs that we could create?
  1. We could create a graph comparing the duration of the campaign versus the outcome to understand if the campaign duration had any impact in achieveing targets.
  2. We could create the graphs per country to see if there are any regional trends that surpass global trends. 
