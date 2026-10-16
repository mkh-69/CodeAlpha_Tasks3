# Machine Learning Tasks Collection

This repository contains three machine learning projects implemented in
Python using Jupyter Notebooks. The tasks cover **credit default
prediction**, **handwritten character recognition**, and **heart disease
prediction**.

## Projects

### 3. Disease Prediction from Medical Data

**Folder:** `Disease Prediction from Medical Data`

This project predicts the presence or absence of heart disease using
medical patient data and compares three machine learning algorithms.

#### Dataset

-   File: `heart-disease-cleveland.csv`
-   Records: 303
-   Features: 13
-   Target: `diagnosis`

The original target contains multiple disease levels. It is converted
into a binary classification problem:

-   `0` → No Disease
-   `1` → Disease

#### Models Used

-   Logistic Regression
-   Random Forest
-   Support Vector Machine (SVM)

#### Methodology

-   Loaded the CSV dataset
-   Checked missing values and dataset information
-   Replaced `?` values with missing values
-   Converted columns to numeric values
-   Cleaned column names
-   Converted the target into binary classes
-   Filled missing feature values using median imputation
-   Split the data into training and testing sets
-   Applied feature scaling for Logistic Regression and SVM
-   Trained and evaluated all three models
-   Compared model accuracies
-   Selected the best-performing model
-   Generated a confusion matrix and classification report
-   Tested the final model on a sample patient

#### Results

  Model                     Accuracy
  --------------------- ------------
  Logistic Regression         86.89%
  Random Forest           **88.52%**
  SVM                         85.25%

**Best Model:** Random Forest\
**Best Accuracy:** **88.52%**

## Important Notes

-   The notebooks contain the complete data preprocessing, model
    training, evaluation, and prediction workflow.
-   Results can vary slightly when the notebooks are retrained in a
    different environment or with different library versions.
-   The disease prediction project is an educational machine learning
    project and should not be used as a substitute for professional
    medical diagnosis.
-   The credit scoring model is also intended for educational purposes
    and should not be treated as a production financial decision system
    without further validation.

## Author

**Muhammad Khursheed**

**BSCS --- Minhaj University Lahore**

## License

This project is intended for educational and academic purposes.
