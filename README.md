# Telco Customer Churn Prediction

I have developed a supervised machine learning model to predict customer churn in the telecommunications sector using customer data analysis.


This project analyzes customer data to identify key factors driving churn in the telecommunications industry, aiming to reduce attrition and boost profitability.

💾 **Project Files Description**

This project includes one main Jupyter Notebook file and one CSV dataset file, as well as relevant output files:

- **Main Jupyter Notebook:**
  - **Churn_Prediction.ipynb** - This notebook includes all functions required for data preprocessing, model training, and evaluation.

- **Dataset Overview:** 
  - The dataset contains information on **7,043** customers, including **21 columns** such as customer ID, gender, age, tenure, monthly charges, contract type, internet service type, and the target variable indicating whether a customer has churned.

- **Output Files:**
  - **Telco_Customer_Churn.csv** - This file includes all relevant customer data used for analysis and modeling.
  - **Random_Forest_Model.pkl** - This file stores the trained Random Forest model, allowing for quick access to churn predictions without the need to retrain.

📖 **Project Summary**

This project focuses on customer churn in the telecommunications sector, aiming to build a predictive model that identifies customers at risk of leaving. The analysis involves:

- **Data Exploration:** Understanding the dataset structure and cleaning it for analysis, with detailed checks revealing a churn rate of **26.54%** (1,869 out of 7,043 customers).

- **Feature Engineering:** Utilizing techniques such as one-hot encoding for categorical variables and scaling for numerical values to prepare the data for modeling.

- **Modeling:** Employing the Random Forest algorithm due to its high accuracy of **89.05%**, precision of **86.24%**, and recall of **95.61%**, ensuring effective identification of at-risk customers.

- **Evaluation:** Using metrics like accuracy, precision, and recall to assess model performance, achieving an overall F1 score of **90.69** and an AUC score of **0.97**, indicating the model's strong predictive capabilities.

📋 **Execution Instructions**

**Churn_Prediction.ipynb**

1. **Load the Dataset:** Execute the Jupyter Notebook to load the CSV dataset and perform initial checks for data integrity and quality.
   
2. **Data Preprocessing:** Follow the defined steps in the notebook to clean and preprocess the data, including handling missing values and categorical encoding.

3. **Model Training:** Implement the Random Forest model using the specified parameters, optimizing for performance with techniques like grid search for hyperparameter tuning.

4. **Model Evaluation:** Assess the model using the evaluation metrics outlined, ensuring that the results meet business objectives for reducing churn.

This project offers valuable insights into customer behavior, allowing telecommunications companies to implement targeted retention strategies to enhance customer loyalty and profitability.
