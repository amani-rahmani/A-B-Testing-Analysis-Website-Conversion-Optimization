# A-B-Testing-Analysis-Website-Conversion-Optimization
This project evaluates the impact of a new website experience (treatment group) compared to the existing version (control group) using A/B testing methodology.  The analysis demonstrates an end-to-end experimentation workflow, including data cleaning, exploratory analysis, hypothesis testing, and business interpretation using realistic data.
## Business Objective

Determine whether the treatment version of the website leads to a statistically significant increase in click-through rate (CTR) and provide a data-driven recommendation.
### Project Workflow
### Data Cleaning & Preparation

* Standardized inconsistent group labels

* Addressed casing issues and missing values

* Verified experiment group integrity

### Exploratory Data Analysis (EDA)

* Calculated CTR by group

* Analyzed CTR by device type

* Compared session duration across groups

### EDA Observation:
* The treatment group showed a slightly higher CTR across most segments.

### Hypothesis Definition

* Null Hypothesis (H₀): The treatment does not change CTR.

* Alternative Hypothesis (H₁): The treatment increases CTR.

*  A one-tailed test was chosen to reflect the business goal of improvement.
### Statistical Testing

* A two-proportion Z-test was conducted to validate whether the observed CTR difference was statistically significant.

### Results:

*  Z-score: 1.44

*  p-value: 0.0747

* 95% Confidence Interval: [-0.004, 0.066]

* At a 5% significance level, the p-value exceeds the threshold, and the confidence interval includes zero.

###  Conclusion:
* There is insufficient statistical evidence to conclude that the treatment improves CTR.

### Business Recommendation

* While the treatment group demonstrated a positive trend in CTR, the results were not statistically significant.

### Recommendation:
Bussiness owner should not roll out the treatment globally at this stage.
Instead should :

* Run the experiment longer to increase power

* Test additional variations

* Segment further by user behavior or acquisition channel
