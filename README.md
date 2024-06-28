# Risky-credit-analysis

Dataset download link: https://www.kaggle.com/datasets/faryalzafarbhatti/credit-risk-model-dataset?select=cs-test.csv

# Columns

Necessary explanations about the columns are written in the Data Dictionary.xls

# Dataset

Risk labels are unbalanced. Columns 'MontlyIncome' and 'NumberofDependents' are read as string type from Pyspark.Dataframe.

# Python IDE

Google Colab service was used for Jupyter Notebook. Therefore, Java Virtual Environment was not implemented. 
If you are going to use pyspark on your local computer, do not forget to install JDK and Spark; and edit the Spark path.

# Model Metrics

Cross validation method was applied to test and train datasets. Since recall, precision, F1 scores are above 80 percent for both datasets, we encounter an acceptable model.
