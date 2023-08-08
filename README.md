# News-Classification
The repository aims at classifying the news articles between various sub-categories.

The dataset was taken from Kaggle.
Link for the dataset : https://www.kaggle.com/datasets/rmisra/news-category-dataset

This dataset contains around 210k news headlines from 2012 to 2022 from HuffPost. This is one of the biggest news datasets and can serve as a benchmark for a variety of computational linguistic tasks.

The file contains 210,294 records between 2012 and 2022. Each JSON record contains the following attributes:
category: Category article belongs to
headline: The headline of the article
authors: The person who authored the article
link: Link to the post
short_description: Short description of the article
date: Date the article was published

The dataset contains imbalanced data. Therefore resulting in biasing of the data. This is removed by applying the "Oversampling" method.

The News Headlines were taken as features and each category was numbered and was taken as the label.
Feature Engineering Technique of 'TF_IDF Vectorizer' was applied.
The data was trained on the Naive Bayes model.

The accuracy and F1-score achieved was 76%.
