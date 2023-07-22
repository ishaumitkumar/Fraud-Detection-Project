# Project
a) Purpose of the Project:
In this fast-changing world, there have been multiple cases of fraudulent bank transactions and there have been very few systems to verify such cases.
So in order to check whether an application entered by the customer is legitimate or not, we have developed a model to verify the applicant's details.

b) Collection of Data:
We have surfed the data through various online portals, through which we figured out
that the dataset available at the Neurl IPS2022 conference was suitable for the problem statement.
The Bank Account Fraud (BAF) suite of datasets comprises a total of 6 different synthetic bank account fraud tabular datasets.
The data has almost 11 thousand fraudulent records against 10 million non-fraud accounts.

c) Data Preprocessing:
Initially, while exploring the dataset, it was discovered that it is highly unbalanced. So Data Cleaning  and Feature selection on the data included Robust Scaling for numerical data and One Hot Encoding for categorical data. 
In the end, a new file(final.csv) was saved which included both modifications.

d)Data Modeling:

After data preprocessing, we performed a train-test split on the newly cleaned data file and applied a set of different algorithms.
Based on the metrics, the parameter F1 Score still seemed to be too off and gave us bad results.

Now, based on the findings, Random Under Sampling, Near Miss Sampling, Tomek Links, and Edited Nearest Neighbour were performed on the data, and various algorithms including Random Forest, SVM, and ANN were also applied.

Based on the result of these findings, Near Miss Sampling gave a good F1 score. 
Initially, while applying various algorithms through Random Under Sampling, the Random Forest and SVM gave decent results(F1-Score) but ANN was not performing well.
Only after hyper tuning of parameters was performed, like increasing the number of dense layers, dropout rate, and learning rate, ANN gave the good F1 score, we were hoping for.

e)Conclusion:
After Random Under Sampling and Near Miss Sampling, both False Positives and False Negative were significantly reduced.
We utilized Classification Report and Matthew's Co-relation coefficient as metrics for our model.




[Link to Drive](https://drive.google.com/drive/folders/1JDCJN3Dx7XG-XaYMHgghcKy20O3S73xU?usp=drive_link)


 





