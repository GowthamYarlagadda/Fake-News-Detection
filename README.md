# Fake-News-Detection
This project was learnt in Coursera and is for anyone with foundation in programming and machine learning who wants to develop Data science and Machine learning projects but having limited resources on their computer and limited time.

## Objective
- To create a filter that will clear all the inaccurate news.

## Components of Code 

- Importing files from gdrive through pydrive
- Authentication of user
- Converting .csv files to pandas DataFrames
- Find missing values and removing them
- Seaborn plots for info
- Merging into one dataset for training
- Removing punctuation marks
- Training by using deep learning technique
- Model creation and training
- MLP binary classifier
- Model Evaluation
- Saving and downloading your model (.pkl File)
- Model deployment


#### Some important points
 -->What is an id? Words existing between "d/" and "/view" of google drive link of the file.

-->We can see that no of fake news and true news varies a bit much. We need not to consider any SMOTE analysis (replicating some values so that they become equal). Because in this project,It is better to have model that can detect more Fake news.

-->Why removing Punctuation marks?The system doesn't need them and they doesn't make much difference in the result. they also increase our training period

-->CountVectorizer: This does the process of vectorization (token-ize) which is one of the deep learning process. Simply all inputs are stacked into matrix.

--TfidfTransformer: This does the process of normalization of inputs.

-->Multi-layer Perceptron (MLP) binary classifier: it is one of the best binary classifier which computes the prediction using pipelines where all calculations are linked and be done at single time.

-->A pickle (.pkl file):A PKL file is a file created by pickle, a Python module that enabless objects to be serialized to files on disk and deserialized back into the program at runtime.


| Files | sources |
| ------ | ------ |
| Fake and real news dataset | [https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset][PlDb] |
| Pydrive Documentation | [https://pythonhosted.org/PyDrive/][PlGd] |
|Drive REST API| https://colab.research.google.com/notebooks/io.ipynb





   [PlDb]: <https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset>
   [PlGh]: <https://colab.research.google.com/notebooks/io.ipynb#scrollTo=jRQ5_yMcqJiV>
   [PlGd]: <https://pythonhosted.org/PyDrive/>
