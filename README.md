![image](https://github.com/AdeWT/Superstore-Membership-Predictor-Project-AdeWT/assets/150229255/2f4debfd-e3e0-42d7-8c97-0e9963bcd97a)


# Superstore Membership Predictor Project
Classification machine learning project of predicting whether a superstore customer will buy a membership or not

# Preface

The author is a data scientist working in a research firm, doing a custom machine learning project for a superstore client.

The client is planning to distribute membership discount offer to customers by phone calls, and want to focus their effort on customers more likely to accept the offer. Data of last year's similar campaign is then given to the author for machine learning creation to predict whether a customer will or will not buy a membership based on several factors.

---

# Data Exploration

Data is obtained from [Kaggle](https://www.kaggle.com/datasets/ahsan81/superstore-marketing-campaign-dataset). Exploratory Data Analysis is then done in Python using Pandas, Statistics, Scipy, Matplotlib, and Seaborn libraries. 

# Machine Learning

Machine learning were done with Scikit-Learn library. Random Forest gave out the best result in standard parameter, and is then hyperparameter-tuned.

Result of data exploration and machine learning can be seen in the report [here.](https://github.com/AdeWT/Superstore-Membership-Predictor-Project-AdeWT/blob/main/SMPP_deliverable_slides.pdf)

## Machine Learning: Technical Challanges and Recommendation

The main challange were that of limited time frame to focus and try out different models. The unbalanced data is also a challange and undersampling, where we decrease the target data with higher occurence, should be done instead of oversampling, where we impute/create new data of the target with lower occurence, as this ends in low classification model performance.

Also due to time constraint, further data exploration and feature selection was not done, and it should be done in future projects to improve model performance. 

PCA should also be tested out if it will give out better results. It was not tested out due to fear of taking out too much information out of the model, and time constraint. 
