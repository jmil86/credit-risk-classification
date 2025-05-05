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




**Coding Approach**
1. Load the Data
Imported the CSV file into a Pandas DataFrame.

Reviewed the first few rows to understand the dataset structure.

2. Separate Features and Labels
Set the loan_status column as the target variable (labels).

Used the remaining columns as feature variables (features).

Reviewed the unique target values to confirm binary classification.

3. Split the Data into Training and Testing Sets
Split the dataset into training and testing sets using a fixed random state for reproducibility.

4. Train a Logistic Regression Model
Instantiated a Logistic Regression model with a random state.

Trained the model using the training feature and label sets.

5. Make Predictions
Used the trained model to predict outcomes on the test dataset.

Previewed sample predictions to verify output format.

6. Evaluate Model Performance
Generated a confusion matrix to assess true positives, true negatives, false positives, and false negatives.

Printed a classification report showing precision, recall, f1-score, and overall accuracy.