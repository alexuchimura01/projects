# Projects by Alex Uchimura

## Overview
Welcome to my GitHub repository! Here you will find a collection of some of the data analysis projects that I have worked on. This is a dynamic repository that will continue to be updated with projects of various foundational data science concepts. 
___
___
### Analzing Technology Sales Representatives: The Impact of Traits on Employee Metrics
Project Description: Worked as a team of four MSBA students to conduct business analysis on a big dataset. Cleaned data on 21,990 hardware and software sales representatives from a large technology company including employee performance metrics, demographics, peer feedback, customer satisfaction indicators, other identifying factors to help answer: 1) What is the ideal tech sales representative? 2) Which variables best predict feedback and net promoter score (NPS)? 3) How can the data assist in salary negotiations? Used both supervised (linear regression and regression trees) and unsupervised (K-means analysis and principal component analysis) learning methods to provide recommendations on employee placement, salary negotiaion, and certification sponsoring to increase higher peer and customer feedback. Findings included that the ideal tech sales rep has explorer or diplomat personality types on average (higher correlation with higher NPS/feedback), firms should prioritize certification sponsorship and employee retention, and that our regression tree is a great option to negotiate salaries from the firm's perspective due to an MPE of -5.1% (underestimates salaries by about 5%). 

Course: GSB 530 - Data Mining and Analytics for Business

Skills Used:
- Data Cleaning
- Data Visualization
- Exploratory Analysis
- Model Tuning/Cross Validation
- Unsupervised Learning (K-means and PCA)
- Supervised Learning (Linear regression and regression tree)

Technologies Used:
- R Studio
- Microsoft Excel/Word

Files:
- [Report](Reports/Tech_Sales_Reps_Final_Report.pdf)

___

### Kaggle - Predicting Political Affiliation
Project Description: Kaggle competition as part of final assessment for Computing and Machining Learning for Business Analytics. Examined a subset of political affiliation data from March 2018 by Survey Sampling International which included survey questions and responses regarding demographics, psychographics, and general political outlooks of survey participants. Created multiple classification models to predict political affiliation (Democrat, Republican, or Independent) on training data provided by Kaggle using accuracy as the preferred competition model metric. Initial attempt at a logistic regression model yielded the highest accuracy compared to other models on the training data (0.6275). Therefore, a logistic model with all predictors and generally balanced tuned parameters yielded a test data accuracy of 0.6024.

Course: GSB 544 - Computing and Machine Learning for Business Analytics 

Skills Used:
- Classification (Logistic Regression)
- Model Tuning/Cross Validation
- Model Pipelines

Technologies Used:
- Python
- Scikit-learn

Files:
 - [Political Survey Data](Data/CAH-201803-train.csv)
 - [Kaggle Codebook](Codebooks/take_home_final.ipynb)

___

### Kaggle - Predicting House Prices
Project Description: Kaggle competition as part of final assessment for Computing and Machining Learning for Business Analytics. Used a dataset with information about properties sold in Ames, Iowa (compiled by Dean De Cock) to form a model that predicts Sale Price. Missing values were abundantly present in the 'Lot Frontage' variable, so a small Random Forest model was implemented to create predictions 'Lot Frontage' missing values. Many models were attempted to yield the lowest possible Root-Mean-Squared-Error (Kaggle's competition metric of choice). These included ridge, lasso, and elastic net models with various combinations of predictor values. Coefficient analysis was used for dimension reduction, revealing that variables like 'TotRms AbvGrd' and 'Lot Frontage' (to name a few) created too much noise that hindered predictive accuracy. The best proposed model was a ridge regression model with resulting RMSE values of 0.1353 and 0.14609 on the training and test data, respectively. This model outperformed other models due to a polynomial term on 'Gr Liv Area'. Please see the attached codebook for further analysis. 

Course: GSB 544 - Computing and Machine Learning for Business Analytics 

Skills Used:
- Data Cleaning
- Random Forest
- Regression (Ridge, Lasso, Elastic Net) 
- Model Tuning/Cross Validation
- Model Pipelines

Technologies Used:
- Python
- Scikit-learn

Files:
 - [Housing Price Data](Data/train_new.csv)
 - [Kaggle Codebook](Codebooks/take_home_final.ipynb)

___

### Model Metric Classification Methods with Cannabis Strains
Project Description: 

Course: GSB 544 - Computing and Machine Learning for Business Analytics 

Skills Used:
- Data Cleaning
- Data Visualization
- Classification (Decision Tree, SVC, SVM, LDA, QDA, Logistic Regression)
- Model Tuning/Cross Validation
- Model Pipelines
- Model-Metric Analysis

Technologies Used:
- Python
- Scikit-learn
- Matplotlib 

Files:
 - [Report (Markdown File)](https://github.com/alexuchimura01/projects/blob/47d60840c0877f05df0b274a93633a0866df07f8/Reports/Cannabis_Multiclass_Classification.html)
