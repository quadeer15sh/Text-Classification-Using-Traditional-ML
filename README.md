# Text Classification Using Traditional ML

Text classification also known as text tagging or text categorization is the process of categorizing text into organized groups. By using Natural Language Processing (NLP), text classifiers can automatically analyze text and then assign a set of pre-defined tags or categories based on its content.

![This is an image](https://api.allganize.ai/static/img/new/text-classification.gif)

## Twitter Tweets Sentiment Classification
- Sentiment classification is the automated process of identifying opinions in text and labeling them as positive, negative, or neutral, based on the emotions customers express within them
- Here since the labelled data that we have only has 2 classes, 0-Negative, 4-Positive (later encoded as 1) we will perform a binary classification

Dataset Used: https://www.kaggle.com/datasets/kazanova/sentiment140

## Data Analysis and Modelling Pipeline
1. Text Cleaning
2. EDA and Visualization
3. Feature Extraction and Modelling
4. Identifying patterns in Extracted Features
5. Running Inference Pipeline

## Python Libraries Required
```
pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn
pip install nltk
pip install scikit-learn
pip install spacy
pip install tqdm
pip install wordcloud
```

Several other machine learning models can also be tried out, but due to the large dataset size small samples need to be taken for training. However for deep learning based models we can do the batch wise training to train our models
