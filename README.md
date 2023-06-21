# Project
a) Purpose of the Project:
In this fast changing world, there have been multiple cases of Bank Fraudulent transactions and there have been very few systems to verify such cases.
So in order to check whether an application entered by the customer is legitimate or not, we have developed a model to verify the applicants details.

b) Collection of Data:
We have surfed the data through various online portals , through which we figured out
that the dataset available at neuraliips2022 conference was suitable for problem statement.
The Bank Account Fraud (BAF) suite of dataset comprises a total of 6 different synthetic bank account fraud tabular datasets.
The data has almost 11 thousand fraudulent records against 10 million non-fraud accounts.

c) Data Preprocessing:
Initially, while exploring the dataset, it was discovered that the dataset is highly unbalanced dataset. So Data Cleaning  and Feature selection on the data was performed which included Robust Scaling for numerical data and One Hot Encoding for categorical data. 
In the end, a new file(final.csv) was save which included both the modifications.

d)Data Modeling:

After data preprocessing, we performed a train test split on the new cleaned data file and applied a set of different algorithms.
Based on the metrics ,the parameter F1 Score still seemed to be too off and gave us bad result.

Now,based on the findings, Random Under Sampling, Near Miss Sampling, Tomek Links and Edited Nearest Neighbour were performed on the data, and various algorithms including Random Forest, SVM, ANN were also applied.

Based on the result of these findings, Near Miss Sampling gave good F1 score. 
Initially, while applying various algorithms through Random Under Sampling, the Random Forest and SVM gave decent results(F1-Score) but ANN was not performing well.
Only after hypertuning of parameters were performed, like increasing number of dense layers , dropout rate and learning rate, ANN gave the good F1 score, we were hoping for.

e)Conclusion:
After Random Under Sampling and Near Miss Sampling, both False Positives and False Negative were significantly reduced.
We utilized Classification Report and Matthew's Co-relation coefficient as metrics for our model.


[This is how a link is added to the readme file using square brackets, 
put the link in round brackets and the statement in square brackets next to each other]

[Link to Drive](https://drive.google.com/drive/folders/1JDCJN3Dx7XG-XaYMHgghcKy20O3S73xU?usp=drive_link)


 





