![banner](abuse.png)
# DukeDataFest2021
Survey Data was sponsored by the *Rocky Mountain Poison and Drug Safety Center* and took place from March 2019 to May 2019 (2 months).

## **Results**: Useful for *both* parties at the Center:
- *Clinicians*: Find the 22 most useful features and accompanying survey questions while keeping the same **90% predictive accuracy**.
- *Population*: Reduces the number of survey questions by 33 thereby **reducing survey completion time from 15 minutes to 2 minutes**.

### The Languages and Technologies used in this project are:
- Visualization: Seaborn, Matplotlib
- Data Manipulation: Pandas, Numpy
- Machine Learning - models included are:
  - Scikit-Learn
    - Logistic Regression
  - Statsmodels.api
    - Logit
  - XGBoost
    - XGBoost Classifier

### Outline the 4D Process:
  1. **Define** the Problem(s)
    - *Inference*: Can we use the accompanying survey data to find which survey questions or features significantly predict the portion of the population that abuses opioids?
    - *Prediction*: To what degree of accuracy can we predict whether an individual will abuse opioids 
  2. **Discover** Inights and Trends
    - Understand the Numerical and Categorical data:
        1. **Categorical**
            - **Region**: Majority of the Respondents were from the South
            - **State**: California had the most responses
      - Identify outliers, missing, and duplicate (and correlated) data
        - Remove features that had high missing data (did not impute values to protect the integrity of the data)
        - Also removed columns or features that had high pearson correlations
      - Understand Distributions of each of the features:
        - More than 50% of the respondants had abused opioids
  3. **Develop** Classification Models
      - Logistic Regression
      - Logit Regression
      - XGBoost Classifier
  5. **Deploy** Data Solution through an interactive Dashboard
      - *NOTE*: Time restrictions and resources prevented a workable dashboard or app to be deployed
