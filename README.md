# ARIMA BondYields
Topic: Predicting US Bond Yields, Using Supervised and Unsupervised Learning Techniques
Introduction:
Goal: Expanding upon the groundwork established by Lih Chyun Shu and Ju-Kun Chou in their 2021 research, this project endeavors to elevate bond yield prediction through the integration of supplementary features and the utilization of various machine learning methods. This project aims to generate a comparative analysis between the various supervised and unsupervised approaches we plan to implement, building upon the foundation laid by the aforementioned study. This data is important and useful because accurate bond yield prediction is crucial for investors, financial institutions, and policymakers. It enables them to make informed decisions regarding bond investments, risk management, and monetary policy formulation. Improving the accuracy of bond yield forecasting can lead to better allocation of resources, reduced financial risks, and improved economic outcomes.


Challenges and Limitations: The dataset is noisy and volatile. The black-box nature of some machine learning models can make interpreting and explaining predictions difficult. There are also variations in data frequencies across different variables. The challenge lies in accurately modeling the complex nature of financial markets. The limitations are primarily from the quality of the sourced data, and the inherent unpredictability of future market environments.


Previous Work:  Lih Chyun Shu, Ju-Kun Chou (2021) “ Using Deep Learning Techniques to Predict 10-Year US Treasury Yield”. https://ieeexplore.ieee.org/iel7/9440550/9440551/09440560.pdf
Dataset: 
The 10-year bond yield data (dependent variable)  is: ^TNX.csv, link:  https://finance.yahoo.com/quote/%5ETNX/history?p=%5ETNX
Independent variables data including macroeconomics, microeconomics, financial indicators come from many resources: Federal Reserve Economic Data (FRED), https://fred.stlouisfed.org/, Bureau of Labor Statistics (BLS) https://beta.bls.gov/dataQuery/find?removeAll=1, Congressional Budget Office (CBO) https://www.cbo.gov/data/budget-economic-data.
Part A: Supervised Learning
Goals: To forecast Treasury 10-year bond yields upon prior bond yield data and additional prior financial indicators.
Learning Approaches: Recurrent Neural Networks (RNNs), Long Short-Term Memory (LSTM) networks, ARIMA
Feature Representations: (1) Target: 10-year US bond yield (2) Features: Interest rates, inflation figures, unemployment rates, consumer prices, US Government budget, GDP, etc.
Computing Platform: Jupiter notebook, Great Lakes
Evaluation Metrics: Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE), Mean Absolute Error (MAE)
Visualization Methods: Feature importance plots and residual plots to analyze model fit
Part B: Unsupervised Learning
Goal: To use unsupervised learning techniques to discover possible underlying patterns and relationships within the data that improve supervised learning accuracy.
Data Manipulation: Cleaning and preprocessing (standardization, missing value imputation, outlier handling), Feature engineering and transformation (domain knowledge-based feature engineering, non-linear transformations), Data merging and integration (data alignment, feature selection, data fusion)
Unsupervised Learning Approaches: Autoencoders,  Generative Adversarial Networks (GANs)
Feature Representations: Analyze reconstruction error in autoencoders, Describe the discovered features and their relationships, and Explain how features might be used in downstream supervised prediction models
Evaluation: (1) Intrinsic evaluation: Reconstruction error (2) Extrinsic evaluation: Use engineered features in a supervised learning task and evaluate model performance
Visualization Methods: Encoded feature space, Reconstructions

Team Planning:

Activities
Date
Takao Kakegawa
Dwight Ross
Tung Nguyen
Project Topic Selection
 Jan 11, 2024 
x
x
x
Draft Project Proposal 
 Jan 16, 2024   
x
x
x
final project Proposal
Jan 20,2024
x
x
x
First Slack Stand-up Reports 
 Feb 11, 2024
x
x
x
Second Slack Stand-up
 Feb 23, 2024
x
x
x
Final project report
Mar 4,2024
x
x
x


Team Contributions:
Data Collection and Preprocessing: Tung Nguyen, Takao Kakegawa, Dwight Ross
Model Development: (RNN) Tung Nguyen, (LSTM) Takao Kakegawa, Dwight Ross (ARIMA)
Pattern Analysis: Autoencoders (Takao Kakegawa), (GANs) Dwight Ross, (Visualization) Tung Nguyen
Model Analysis and Evaluation: Tung Nguyen, Takao Kakegawa, Dwight Ross
Report Writing and Presentation: Tung Nguyen, Takao Kakegawa, Dwight Ross

