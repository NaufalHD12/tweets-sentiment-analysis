# Submission 1: Tweets Sentiment Analysis
Name: Naufal Hadi Darmawan  
Username dicoding:naufalhd12

| | Description |
| ----------- | ----------- |
| Dataset | [Sentiment Analysis Dataset - Binary Classification](https://www.kaggle.com/datasets/dineshpiyasamara/sentiment-analysis-dataset) |
| Problem Description | The primary problem addressed in this project is the classification of tweets into binary sentiment categories, typically positive or negative. This involves analyzing the text of tweets to determine the underlying sentiment expressed. |
| Machine Learning Solution | The solution involves building a machine learning pipeline that processes the input tweet data, applies data transformations, trains a model, and evaluates its performance. The pipeline is designed to automate the stages of data ingestion, validation, preprocessing, model training, evaluation, and deployment.|
| Data Processing Method | The data processing method uses TensorFlow Extended (TFX) components. The pipeline includes stages for data ingestion with **CsvExampleGen**, statistics generation with **StatisticsGen**, schema generation with **SchemaGen**, anomaly detection with **ExampleValidator**, and data transformation with **Transform**. |
| Model Architecture | The model architecture is a binary classification model built using TensorFlow and Keras. It includes a text vectorization layer, an embedding layer, global average pooling, dropout layers, and dense layers. The model is compiled with binary cross-entropy loss and the Adam optimizer. |
| Evaluation Metrics | The evaluation metrics used to assess the model's performance include AUC (Area Under the Curve), binary accuracy, false positives, true positives, false negatives, and true negatives. The binary accuracy metric includes a threshold to ensure significant improvements in accuracy. |
| Performa model | The model achieved a high AUC of 0.94, indicating strong discrimination between positive and negative sentiments. The binary accuracy was 0.89, reflecting good overall performance. There were 72 false negatives and 99 false positives, suggesting areas for potential improvement in reducing these errors. |