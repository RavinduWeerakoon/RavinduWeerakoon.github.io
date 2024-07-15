---
layout: page
title: Employee Attrition analysis
description: A datascience project to analyse the reason fo high rate of employee resignations
img: assets/img/12.jpg
importance: 1
category: Machine Learning
related_publications: true
---

**Project Overview:**

This project aimed to analyze employee attrition at an anonymous construction firm to provide valuable insights for the company's CEO. The goal was to help the CEO make strategic decisions to improve employee retention and overall organizational stability.

**Data Integration and Preprocessing:**

1.  **Data Integration:**

    -   Employed advanced data integration techniques to consolidate multiple data frames.
    -   Ensured seamless merging of disparate datasets for a comprehensive analysis.
2.  **Imputation Techniques:**

    -   Applied the K-Nearest Neighbors (KNN) imputer to handle missing values effectively.
    -   Focused on critical columns such as "Date of Birth" and "Marital Status" to maintain data integrity.

<div class="row justify-content-sm-center">
  <div class="col-sm-6 mt-3 mt-md-0">
    {% include figure.liquid path="assets\img\project1\net_salary.png" title="net salary distribution" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-6 mt-3 mt-md-0">
    {% include figure.liquid path="assets\img\project1\year_of_birth.png" title="birth year distribution" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
    KNN imptation for the two categories and the one which deals less damage to the distribution was taken
</div>
3.  **Data Processing:**

    -   Utilized various data processing techniques to clean and prepare the dataset for modeling.
    -   Ensured that the processed data was robust and suitable for accurate model training.

**Model Training and Evaluation:**

-   **Model Selection:**
    -   Trained an XGBoost (XGB) model to predict employee attrition.
    -   Evaluated the model's performance, achieving an impressive accuracy of 0.89.
-   **Model Validation:**
    -   Analyzed the confusion matrix to verify the effectiveness of data transformations and imputations.
    -   Confirmed that the imputations significantly contributed to the model's predictive power.

    <div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets\img\project1\feature_importance.png" title="Feature Importance" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div

**Key Insights and Recommendations:**

Through comprehensive analysis and evaluation of feature importances, the project provided actionable insights, leading to the following strategic recommendations:

1.  **Hiring Practices:**

    -   Increase the proportion of permanent employees.
    -   Reduce reliance on contract-based hires to enhance job security and loyalty.
2.  **Compensation Strategies:**

    -   Increase employee salaries, particularly for those with critical job roles.
    -   Recognize that employees with higher salaries are more likely to remain with the company.
3.  **Incentive Programs:**

    -   Implement targeted incentive programs to retain employees in the "Labor" category.
    -   Focus on providing benefits that directly address the needs of labor-intensive roles.

**Technolgies Used**
-   Google Colab
-   Python

All the code and the dataset associated with the project can be found on [here](https://github.com/RavinduWeerakoon/Employee-Attrition-Analysis)