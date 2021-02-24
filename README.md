# Credit_Card_Fraud_Detection_overview

In this notebook, I learn about a detection problem dealing with the imbalanced data between fraud and non-fraud transactions in the bank environment. The two most things I have learned from this notebook the two ways to face with the very imbalanced dataset. Especially, in the fraud or malware detection problems, that includes random 
**Undersampling** and **Oversampling**.


I want to express my big thank to an author of this https://www.kaggle.com/janiobachmann/credit-fraud-dealing-with-imbalanced-datasets notebook on Kaggle site. I have so much learned his amazing techniques in this document. 

For the technique of random under sampling and over sampling, I would like to propose this reference link: https://dataman-ai.medium.com/sampling-techniques-for-extremely-imbalanced-data-part-i-under-sampling-a8dbc3d8d6d8

And, following the above link reference and my personal experiences, I present briefly here my approaches. 

**Perpectives**

I am gonna work on the new methods dealing with the imbalanced data in the next update. More particularly, I want to consider directly machine learning algorithms while crossing validation corresponding to random over-sampling and under-sampling which I will consider:

* Oversampling techniques SMOTE

* Undersampling techniques Tomek Links, ENN

However, I will consider the 

* Hybridized Sampling

That means, first I will do SMOTE to over sampling randomly the miority class. Then I will apply Tomek Links or ENN to remove the instances of the both class whose prediction made by KNN method is different from the both class. 

We will be more clear in the next update!!! See you!
