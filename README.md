# PROJECT OVERVIEW

Health insurance costs have risen dramatically over the past decade in response to the rising cost of health care services and are determined by a multitude of factors. Let's look at the cost of healthcare for a sample of the population given age, sex, bmi, number of children, smoking habits, and region.

The purpose of this project is to determine the contributing factors and predict health insurance cost by performing exploratory data analysis and predictive modeling on the Health Insurance dataset. This project makes use of Numpy, Pandas, Sci-kit learn, and Data Visualization libraries.

Overview:
• Seek insight from the dataset with Exploratory Data Analysis
• Performed Data Processing, Data Engineering and Feature Transformation to prepare data before modeling
• Built a model to predict Insurance Cost based on the features
• Evaluated the model using various Performance Metrics like RMSE, R2, Testing Accuracy, Training Accuracy and MAE

# DATA DESCRIPTION

1.age: age of primary beneficiary
2.sex: insurance contractor gender, female, male
3.bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
4.children: Number of children covered by health insurance / Number of dependents
5.smoker: Smoking
6.region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest
7.expenses: Individual medical costs billed by health insurance

Data source : https://www.kaggle.com/mirichoi0218/insurance

# INSIGHTS

The insights drawn by performing Exploratory Data Analysis (EDA) are:

• Most people are a non smokers & obese.
• Feature sex, region has an almost balanced amount.
• People who smoke & have a higher BMI, has higher medical charges.
• Older people who smoke have more expensive charges.
• An obese person who smokes have higher charges.

