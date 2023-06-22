# Capstone-Project-Predicting-Likelihood-and-Severity-of-Road-Accidents-In-Victoria
 > My Final Capstone project for General Assmebly's Data Analytics Immersive Course

> 👉 Access the technical report here (Capstone_Said_jomaa_technical_report.pdf)

## Overview
The study aims to create a precise model that predicts the severity of accidents and identifies the key variables that contribute to Severe accidents. The collected road accident data for Victoria, Australia, spanning from 2006 to 2020, is utilized for this purpose. By employing multiple logistic regression, the study identifies the most influential variables on severe accidents and develops an approach for accident prediction. The findings of this research can assist authorities in prioritizing corrective measures to prevent accidents.

## Methodolgy
The data underwent preprocessing to address outliers, missing values, and skewness. Subsequently, additional data transformations were applied through one hot encoding and label encoding. To address data imbalance, two techniques, namely undersampling and SMOTE, were employed, resulting in the creation of two distinct datasets. Multiple iterations of these three steps were performed to conduct the regression analysis:

> * **Step 1:** Select features that go into the model
> * **Step 2:** Develop and adjust model
> * **Step 3:** Assess and validate model

Our final model uses the undersampling data set. The data split is performed with a ratio of 80/20, where 80% of the data is allocated to the training set and the remaining 20% is split equally between the test and validation sets. With a prediction threshold set as 0.65.

## Results
Results show that the logistic regression in the forward stepwise method has an accuracy prediction power of 76.6%. The most contributing factors that lead to severe accidnets are speed zone, road surface conditions, light condtions, urbinisation status and whether safety equipment was worn or not. All of these things can contribute to accidents being more serious.

## Limitations 
limitation of our study was that we had limited access to complete data for conducting the analysis. As a result, the findings of our analysis did not show strong statistical significance. However, we expect that with a larger and more comprehensive dataset, the models used in our study will provide more reliable and conclusive results.

Nevertheless, gaining an understanding of the relationships between the causes of incidents and their outcomes can help identify factors that have the potential to lead to catastrophic events, as well as factors that may result in less severe events. This knowledge can be valuable in mitigating risks and prioritizing measures to prevent accidents.
