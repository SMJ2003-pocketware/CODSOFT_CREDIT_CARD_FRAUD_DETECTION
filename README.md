# CODSOFT_CREDIT_CARD_FRAUD_DETECTION

*COMPANY*: CODSOFT

*NAME*: SOHAM MAJUMDER

*INTERN ID*: CS25NY365911

*DOMAIN*: DATA SCIENCE

*DURATION*: 4 WEEKS

In this project, I worked with a credit card transaction dataset to identify fraudulent transactions. The goal was to build a machine learning model to detect fraud, given that fraudulent transactions are rare and highly imbalanced compared to normal transactions. I began by loading the dataset and examining its structure with basic methods like head(), info(), and describe() to get a sense of the data types, summary statistics, and check for missing values. This helped me understand the distribution and characteristics of the data.

For exploratory data analysis (EDA), I first visualized the distribution of the target variable, "Class," which indicates whether a transaction is fraud (1) or normal (0). I also created histograms to compare the time of transaction for both fraudulent and normal transactions, which showed how these two classes differ in their time distributions. Additionally, I generated a correlation matrix to examine the relationships between different features in the dataset.

The dataset is highly imbalanced, with fraudulent transactions being much less frequent than normal ones, which can affect model performance. To address this, I used the Synthetic Minority Oversampling Technique (SMOTE) to oversample the minority class (fraudulent transactions) during the training phase. I also sampled a smaller subset of the data due to its large size, and performed the same steps to handle class imbalance on the smaller subset.

After preparing the data, I trained a Random Forest Classifier on the resampled training data. I evaluated the model using accuracy and classification metrics, such as precision, recall, and F1-score, to assess how well the model was able to distinguish between normal and fraudulent transactions. The use of SMOTE helped balance the classes and improve the model's ability to detect fraud in an imbalanced dataset. The final model evaluation was conducted using the test dataset, providing insights into its performance in a real-world scenario where fraudulent transactions are rare.


*OUTPUT*

![Image](https://github.com/user-attachments/assets/318ca213-55e2-4db4-9043-2077bcb9ce3a)

![Image](https://github.com/user-attachments/assets/ff1656d4-ffcc-4cfb-aafa-7a9cdb588f9c)

