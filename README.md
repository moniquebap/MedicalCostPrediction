# Medical Cost Prediction
## Dataset Overview:
The medical insurance dataset encompasses various factors influencing medical expenses, such as age, sex, BMI, smoking status, number of children, and region. This dataset serves as a foundation for training machine learning models capable of forecasting medical expenses for new policyholders. Its purpose is to shed light on the pivotal elements contributing to increased insurance costs, aiding the company in making more informed decisions concerning pricing and risk assessment.

The dataset comprises 2.7K rows and 7 columns, including:

- Age
- Sex
- BMI (Body Mass Index)
- Children
- Smoker
- Region
- Charges

Dataset obtained from [Kaggle](https://www.kaggle.com/datasets/rahulvyasm/medical-insurance-cost-prediction)

### Problem Statement:
1. What are the primary factors influencing medical expenses?
2. How accurate are machine learning models in predicting medical - expenses?

### Findings:
1. According to the multiple regression model, being a smoker has the highest impact on charges (the charge is increased by 23899.63 compared to non-smokers). The number of children is shown as the second most important factor (charges increase by 451.12 per child), and BMI is third (charges increase by 327.86 per unit of BMI). Age also appears to be an important factor in determining insurance charges, with an increase of 254.30 per unit increase in age.
2. In this case, the R2 score is approximately 0.74, which means that your model explains about 74% of the variability in the insurance charges.
