# A/B Testing: Advanced Data Analytics Project

The project aims to evaluate the effectiveness of a website landing page redesign through rigorous A/B testing analysis using R.

## 📂 Project Structure

- `ADAproject_2025_data.csv` – Dataset used for A/B testing


## 📊 Project Overview

### Objective
To determine whether the **new landing page** results in a statistically significant increase in user conversion compared to the **old landing page** using A/B testing methodology.

### Dataset Description
The dataset includes the following fields:
- `user_id`: Unique identifier for each user
- `group`: Assigned group (`control` or `treatment`)
- `landing_page`: Page version shown (`old_page` or `new_page`)
- `converted`: Binary outcome (1 = converted, 0 = not converted)
- `timestamp`: Timestamp of page view

---

## 🔬 Methodology

1. **Data Cleaning**  
   - Removed mismatches between group and landing page  
   - Dropped duplicate `user_id` entries  

2. **Exploratory Data Analysis (EDA)**  
   - Calculated conversion rates per group  
   - Visualized distributions over time

3. **Statistical Hypothesis Testing**  
   - **Null Hypothesis (H₀):** Conversion rates for old and new pages are equal  
   - **Alternative Hypothesis (H₁):** Conversion rates differ between the pages  
   - Used a **z-test for proportions** to evaluate significance  



## 🧠 Business Implications

- Recommendation based on data-driven evidence
- Discussed the cost-benefit of implementing the new design
- Highlighted potential limitations and future A/B test improvements


## 🔍 Outcomes and Key Learnings

Through this A/B testing project, we developed and applied key analytical and collaborative skills:

1. **Understanding A/B Testing Principles**  
   Gained practical experience in designing and analyzing A/B tests, including hypothesis formulation and statistical decision-making.

2. **Data Cleaning and Validation**  
   Learned to identify and correct inconsistencies in experimental data (e.g., mismatched treatment assignments and duplicates) to ensure reliable results.

3. **Statistical Testing with R**  
   Applied z-tests for proportions to compare conversion rates and interpret p-values and confidence intervals to assess significance.

4. **Exploratory Data Analysis (EDA)**  
   Visualized and summarized the data using tools like `ggplot2` and `dplyr` to uncover patterns and compare group behaviors.

5. **Business-Oriented Interpretation**  
   Connected statistical results to actionable business insights, weighing potential trade-offs between user experience and conversion rate impact.

6. **Collaboration and Reproducibility**  
   Worked as a team using RMarkdown to produce a reproducible, well-documented report that adheres to professional data analysis standards.




