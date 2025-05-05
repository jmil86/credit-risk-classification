# **Credit Risk Analysis Report**

**Overview of the Analysis**
 * The purpose of this analysis was to build and evaluate a logistic regression model to predict the credit risk of borrowers based on historical loan data. The goal was to accurately identify borrowers who are likely to default (high risk) versus those who are not (healthy loans).

**Results**
* Accuracy Score: 0.99 (99%)

* Precision Score:

    * High-risk loans (1): 1.00

    * Healthy loans (0): 0.84

* Recall Score:

    * High-risk loans (1): 0.99

    * Healthy loans (0): 0.94

    * F1-Score:

    * High-risk loans (1): 1.00

    * Healthy loans (0): 0.89

**Summary**
* The logistic regression model achieved a very high overall accuracy of 99%.
It predicts high-risk loans with near-perfect precision and recall, making it highly reliable for identifying risky borrowers. While the model also performs well in identifying healthy loans, it shows slightly lower precision for this class, meaning there is a small chance of misclassifying healthy loans as risky.

**Recommendation**
* I recommend this model for use by the company because it excels at identifying high-risk loans, which is crucial for minimizing potential defaults. However, additional refinement or complementary models could be considered in the future to further improve performance on healthy loan classification.