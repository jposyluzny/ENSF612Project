# ENSF612Project
This was a group project that was focused on replication. We decided to replicate a paper we found which tried to predict the popularity of Instagram posts based off a wide variety of features, and was a classification task. After replication, we were to extend the paper by training at least one new model. Our process was as follows:
* Obtain the raw data that the paper's authors used
* Use an Instagram Crawler API to gain 1000 new samples
* Process all of the raw data into feature matrices and target vectors
* Train the models that the paper used (XGBoost, Random Forest Classifier) on the old data, and on the extended data (old + new data)
* Train our new model (LightGBM) on the old data, and on the extended data (old + new data)

The paper that we replicated is the Research_Paper PDF file. We managed to at least match their results, surpassing in some sections. We found LightGBM to be an excellent model, in scoring and speed of training. Our findings and report are contained in the ENSF_612_Final_Report PDF file, and the links to the Databricks notebooks which contain our code are found in said report, as well as the Databricks Links text file.
