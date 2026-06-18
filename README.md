# Telco Customer Churn & Lifecycle Segmentation

## Project Overview
This project focuses on identifying key drivers of customer attrition (churn) for a telecommunications provider using Python. By analyzing behavioral attributes, service choices, and customer lifecycles, this analysis uncovers actionable, data-driven insights to optimize customer retention strategies and maximize customer lifetime value (LTV).

## Business Objectives
* **Analyze Attrition Baselines:** Quantify the overall proportion of churned vs. active customers to establish a baseline.
* **Profile Customer Lifecycles:** Segment continuous customer tenure metrics into strategic groups (`0-12 Months`, `13-36 Months`, `37+ Months`).
* **Evaluate Financial Impact:** Compare average monthly costs across segments to identify premium risk categories.
* **Uncover Operational Friction:** Audit service types, contract types, and payment behaviors to isolate friction points causing early lifecycle drop-offs.

## Technical Framework & Tools Applied
* **Pandas:** Executed data cleaning pipelines, standardized malformed column strings to lowercase, handled text-to-numeric type conversions, and engineered custom data bins.
* **Matplotlib & Seaborn:** Structured a comprehensive 2x3 visualization dashboard utilizing custom subplots, multi-layered color configurations, specific axis structuring, and geometric bar annotations.
* **NumPy:** Leveraged arrays for optimized underlying logical segmentation computations.

## Key Strategic Insights Uncovered
1. **The Critical Onboarding Window:** Customers in their first year (`0-12 Months`) represent a massive **31.0%** of the total customer base, yet they suffer from the highest velocity of customer churn. 
2. **Pricing is Not the Initial Friction Point:** Interestingly, the high-churn `0-12 Months` cohort maintains a significantly lower average monthly charge (**$56.10**) compared to the highly loyal `37+ Months` veterans (**$72.01**). This reveals that early attrition is driven by onboarding experience and customer alignment rather than cost.
3. **Operational Vulnerabilities:** High-churn velocities are fundamentally correlated with month-to-month contracts and manual billing channels (Electronic Checks). These mechanisms eliminate friction for customer exit.
4. **The Retention Anchor:** Once a customer crosses the 36-month threshold, their adoption of stable 1-year and 2-year contracts alongside automated payment networks completely locks in loyalty, driving attrition down to negligible baselines.

   ## How to Replicate This Project
1. **Clone the Repository:** ```bash
   git clone [https://github.com/nonyeobi-stack/telco-customer-churn-analysis.git](https://github.com/nonyeobi-stack/telco-customer-churn-analysis.git)

   bash

   jupyter notebook
