<img src="https://github.com/TLCLauraB/credit-risk-classification/blob/main/img/machine-learning-icon-linear-vector-pink-sm.jpg" alt="Vector conceptual art of a brain with computer wires done in a pink and purple motif." width=25% align=left>Module 20 Challenge: Credit Risk Classification Using Supervised Machine Learning <br/>
Presented by Laura Bishop (TLCLauraB)<br/><br/>
Table of Contents:<br/>
    [Folder: Credit_Risk](https://github.com/TLCLauraB/credit-risk-classification/tree/main/Credit_Risk)<br/>
    *    [File: credit_risk_classification.ipynb](https://github.com/TLCLauraB/credit-risk-classification/blob/main/Credit_Risk/credit_risk_classification.ipynb)<br/>
    *    [File: lending_data.csv](https://github.com/TLCLauraB/credit-risk-classification/blob/main/Credit_Risk/lending_data.csv)
<br/>
<br/>
<br/>
<br/>
## Introduction: 
In this challenge, I used various techniques learned in Module 20 to train and evaluate a model based on loan risk. The course provided the dataset and was based on historical lending activity from a peer-to-peer lending service company. I used this to build a model that could identify the creditworthiness of its borrowers. 

## Workflow:
There was no ETL necessary for this assignment. A review showed everything was prepared for me and ready, provided by the starter code.

I received support from my fellow Data Viz classmates during class time, through Slack and via our Discord server. I regularly attended both before and after-class office hours to engage my Instructor and TAs. I reviewed the provided syllabus for Module 20.1 and 20.2 as well as the accompanying class work and instructor examples.

## Analysis:
Classification Report for the Model:<br/>
<img src="https://github.com/TLCLauraB/credit-risk-classification/blob/main/img/classification_report-results.png" alt="Classification report for the model." width=40%>

- **Purpose of the Analysis:**
  - This analysis is aimed to develop a supervised machine learning model, using a peer-to-peer institution's financial dataset, to predict the risk category of loans.

- **Financial Information and Prediction Target:**
  - The data contained financial information related to loans as provided by a peer-to-peer lending institution.
  - The prediction target was the risk category of loans, with binary labels such as 'healthy loan' (0) and 'high-risk loan' (1).
  - They were assigned to Group 1 - Healthy Loan (0) and Group 2 - High-Risk Loan (1).

- **Basic Information about Variables:**
  - Two classes were present: 'Group 1' and 'Group 2.'
  - Group 1 had a significant majority, indicating potential class imbalance.
  - Group 2 was reserved as the data test set.

- **Stages of the Machine Learning Process:**
  1. **Data Preprocessing:**
     - Handling missing values, scaling features, encoding categorical variables. None were to be found.
  2. **Exploratory Data Analysis (EDA):**
     - Understanding the distribution of features, checking for class imbalance. The Stratify function was used to preserve ratios within both groups.
  3. **Model Selection:**
     - Choosing appropriate machine learning algorithms for classification tasks. This was mostly directed by the provided/guided Jupyter Notebook.
  4. **Train-Test Split:**
     - Splitting the data into training and testing sets.
  5. **Model Training:**
     - Training machine learning models on the training set.
  6. **Model Evaluation:**
     - Evaluating models on the testing set using metrics like accuracy, precision, recall.

- **Methods Used:**
  - Logistic Regression: A linear model suitable for binary classification tasks.
  - Train-Test Split with Stratification: Ensuring balanced class distribution in training and testing sets.

- **Machine Learning Model:**
   - **Balanced Accuracy, Precision, and Recall Scores:**
     * Balanced Accuracy: The overall accuracy considering class imbalance.
     * Precision: The ratio of true positive predictions to the total predicted positives.
     * Recall: The ratio of true positive predictions to the total actual positives.

     - **Model Scores:**
       * **Precision:**
         - Group 1: 1.00 (indicating perfect precision).
         - Group 2: 0.87 (indicating high precision).
       * **Recall:**
         - Group 1: 1.00 (indicating perfect recall).
         - Group 2: 0.89 (indicating high recall).

## Recommendation:
The importance of predicting on a binary scale (1s and 0s) can vary depending on the specific goals and requirements of the problem at hand. The context of the problem and the associated costs or consequences of different types of errors play a crucial role in determining which class is more critical to predict accurately.

In this case, the model performs exceptionally well in predicting both Group 1 - Healthy Loans (0)  and Group 2 - High-Risk Loans (1), achieving high precision, recall, and F1-scores for both groups, with an overall accuracy of 99%.

### Resources:
   * [GitHub: Basic Writing and Formatting Syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
   * [Module 20: Supervised Machine Learning](https://bootcampspot.instructure.com/courses/3876/pages/20-supervised-machine-learning?module_item_id=1018544)

