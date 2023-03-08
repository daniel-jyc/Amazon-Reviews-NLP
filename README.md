# Amazon-Reviews-NLP

This is the Amazon Reviews NLP final project for my Big Data Platforms course. For this project, we leveraged Google API and Kaggle API to transfer data directly from Kaggle to Google Cloud Bucket with no involvement of any local machines/ local storages.

The Data analyzing and modeling parts are done using PySpark (See the ML Modeling.py file for details) and Jupyterlab under Google Cloud Dataproc Cluster.

The models we used include Naive Bayes and logistic Classification. In an effort to increase accuracy, we conducted soft voting techniques. The models were tested on unseen datasets and received promising classification accuracy.
