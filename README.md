# Churn-Modelling

### Business Problem
The organisation is a large financial institution that services a large number of customers. Recently , the organisation has noticed an increase in customers who are leaving the organisation and would like to understand why this is happening as well as identify customers who are likely to churn in order to engage and retain those customers. As there is substantial costs involved with reaching customers, the organisation is interested in curating a list of customers to share with its marketing team to begin the engagement process.

### Problem Statement
There is a significant increase in customers churning over the last 12 months. The organisation is therefore looking to reduce customer churn to < 10% within the next 12 months with the expected benefit of increasing revenue by $55m in the next 12 months

### Data Science Activities
1) Conduct exploratory Analysis to understand drivers of Churn
2) Build an initial model to Identify customers likely to churn

### Results:
1) Feature importance refers to the importance of a feature in driving the outcome of churn for each of our respective models as shown above
   Across all models, Age appears to be the most important driver that impacts churn for our customers followed by their activity and number of products they possess

<img width="762" alt="image" src="https://github.com/Subliminated/Churn-Modelling/assets/90996172/ad861922-786e-4e5e-a8cd-35fb109806a2">

2) Both Random Forest Models and Gradient Boosting Models show very good overall performance with a AUC ROC (Area under Curve) score of .95 and .93. High score means both models are very good at identifying customers who will churn.
   Further, the models also have high recall and precision which is important because:
   - High Recall means lower likelihood of false negatives (we fail to identify churning customers) which is a bad outcome for retention
   - High Precision meaning lower likelihood of false positive (non-churning customers predicted as churning) which is costly to engage
<img width="534" alt="image" src="https://github.com/Subliminated/Churn-Modelling/assets/90996172/4bf25b30-c56e-452b-a524-cfad153354bb">
